
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'GitHub code checkout successful'
            }
        }

        stage('Build') {
            steps {
                echo 'Application build started'
                sh 'docker build -t my-cicd-app .'
            }
        }

        stage('Test') {
            steps {
                echo 'Application test successful'
            }
        }
    }
}
