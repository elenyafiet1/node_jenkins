pipeline {
    agent none
    stages {
        stage('Build on Node 1') {
            agent { label 'build-node' }
            steps {
                echo "Running build on Node 1"
            }
        }
        stage('Test on Node 2') {
            agent { label 'build-node' }
            steps {
                echo "Running tests on Node 2"
            }
        }
        stage('Deploy on Node 3') {
            agent { label 'build-node' }
            steps {
                echo "Deploying on Node 3"
            }
        }
        stage('Cleanup on Node 4') {
            agent { label 'build-node' }
            steps {
                echo "Cleaning up on Node 4"
            }
        }
    }
}
