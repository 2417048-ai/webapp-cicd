pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/2417048-ai/webapp-cicd.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the app...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to server...'
            }
        }
    }
}