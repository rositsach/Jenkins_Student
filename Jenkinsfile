pipeline {
    agent any

    stages {
        stage('NPM Install') {
            steps {
                bat 'npm install'
            }
        }
        stage('NPM Audit') {
            steps {
                bat 'npm audit'
            }
        }
        stage('Run Integration test') {
            steps {
                bat 'npm run test'
            }
        }

    }
}