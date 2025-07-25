pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building for develop branch...'
                sh 'echo "Develop branch build"'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests for develop branch...'
                sh 'echo "Develop branch tests"'
            }
        }
        stage('Deliver') {
            steps {
                echo 'Delivering to staging...'
                sh 'echo "Deliver to staging"'
            }
        }
    }
}
