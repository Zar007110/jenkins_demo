pipeline {
    agent any

    stages {
        stage('staging') {
            steps {
                script {
                    echo 'Hello World'
                    sh 'ssh ubuntu@13.231.38.229 "echo Hello World"'
                }
            }
        }
        stage('production') {
            steps {
                script {
                    echo 'Hello World'
                    sh 'ssh ubuntu@13.231.138.224 "echo Hello World"'
                }
            }
        }
    }
}
