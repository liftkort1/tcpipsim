pipeline {
    agent none 
    stages {
        stage('build') {
            agent {
                docker {
                    image 'python:3.12.1-alpine3.19' 
                }
            }		
            steps {
                sh 'python --version'
            }
        }
    }
}