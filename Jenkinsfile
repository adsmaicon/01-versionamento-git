pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
                sh 'virtualenv venv --distribute'
            }
        }
        stage('test') {
            steps {
                sh 'pytest'
            }
        }
        stage('deploy') {
            steps {
                sh 'deploy'
            }
        }
    }
}