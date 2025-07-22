pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/AKSHAYSBHAT666/playwright-hello.git'
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Run Tests') {
            steps {
                sh 'npm test'
            }
        }
    }
}
