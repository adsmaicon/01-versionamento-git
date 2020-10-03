pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'pip3 install -r requirements.txt'
            }
        }
        stage('test') {
            steps {
                sh 'pytest'
            }
        }
        stage('deploy') {
            steps {
                sh 'python --version'
            }
        }
    }
}