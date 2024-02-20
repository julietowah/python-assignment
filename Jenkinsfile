pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Your build steps go here
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                // Your test steps go here
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                // Your deployment steps go here
                echo 'Deploying the application...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline failed. Please check the build logs.'
        }
    }
}
