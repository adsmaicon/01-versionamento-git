pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('test') {
            steps {
                sh 'Testing'
            }
        }
        stage('deploy') {
            steps {
                sh 'deploy'
            }
        }
    }
}