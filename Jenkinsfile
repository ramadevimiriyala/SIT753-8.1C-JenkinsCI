pipeline {
    agent any

    tools {
        nodejs 'NodeJS' // Make sure this matches the name of your NodeJS tool in Jenkins
    }

    stages {
        stage('Build') {
            steps {
                echo 'Installing dependencies...'
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Replace with actual test command if available
                sh 'echo "No test command configured."'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Replace with your deployment logic
                sh 'echo "Deployment complete."'
            }
        }
    }
}
