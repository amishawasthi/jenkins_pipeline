pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/amishawasthi/jenkins_pipeline.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building project..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
    }
}
