pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Poonamamrutrao/flask-app-cicd-jenkins.git'
            }
        }
        stage('Build Docker Image') {
            steps {
                script {
                    docker.build("flask-cicd-jenkins")
                }
            }
        }
        stage('Push to ECR') {
            steps {
                echo 'Push image to ECR - Add your login code here'
            }
        }
    }
}