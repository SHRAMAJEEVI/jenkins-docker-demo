pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git https://github.com/SHRAMAJEEVI/jenkins-docker-demo.git
            }
        }
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running Tests...'
            }
        }
    }
}