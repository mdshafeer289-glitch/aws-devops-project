pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Code checked out from GitHub'
            }
        }

        stage('Test') {
            steps {
                echo 'Application test completed'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker build -t aws-devops-app:v2 .'
            }
        }

    }
}
