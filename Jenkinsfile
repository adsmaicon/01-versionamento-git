pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
                sh 'python3 -m pip install -r requirements.txt'
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