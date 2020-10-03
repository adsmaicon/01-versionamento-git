pipeline {
    agent any
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