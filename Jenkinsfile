pipeline {
    agent none 
    stages {
        stage('build') {
            agent {
                docker {
                    image 'python:3.9' 
                }
            }		
            steps {
                sh 'python3 --version'
            }
        }
    }
}