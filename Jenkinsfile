pipeline {
    agent any
    
    environment {
        APP_NAME = "hello-world"
    }
    
    when {
        branch "master"
    }
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                echo "Application Name: ${env.APP_NAME}"
            }
        }
    }
}
