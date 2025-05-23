pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Installing dependencies...'
                bat 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'node app.js'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                bat 'echo Deploying to environment...'
            }
        }
    }
}
