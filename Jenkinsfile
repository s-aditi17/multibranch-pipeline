pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building for main branch...'
                sh 'echo "Main branch build"'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests for main branch...'
                sh 'echo "Main branch tests"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to production...'
                sh 'echo "Deploy to production"'
            }
        }
    }
}
