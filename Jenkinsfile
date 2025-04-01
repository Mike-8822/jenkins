pipeline {
    agent any
    tools {
        nodejs 'NodeJS 22'
    }
    stages {
        stage('Prepare') {
            steps {
                sh 'node --version'
            }
        }
        stage('Build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('Test') {
            steps {
                sh 'echo $JENKINS_URL'
            }
        }
    }
}