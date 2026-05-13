pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building auth-service..." && sleep 2'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing auth-service..." && sleep 3'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying auth-service to staging..." && sleep 1'
            }
        }
    }
}
// Changes for develop
