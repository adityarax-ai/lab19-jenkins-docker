pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/adityarax-ai/lab19-jenkins-docker.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t my-jenkins-docker-app .'
            }
        }
    }
}