pipeline {

    // Define the agent for the pipeline

    stages {

        // Checkout stage
        stage('Checkout') {
            steps {
                echo 'This is checkout stage'
                git branch: 'main', url: 'https://github.com/johal6132-maker/amazon-app.git'
                echo 'Checkout Completed'
            }
        }

        // Build stage
        stage('Build') {
            steps {
                echo 'This is build stage'
            }
        }

        // Test stage
        stage('Test') {
            steps {
                echo 'This is test stage'
            
            }
        }

        // Docker Build stage
        stage('Docker Build') {
            steps {
                echo 'This is docker build stage'
            }
        }

        // Deploy stage
        stage('Deploy') {
            steps {
                echo 'This is deploy stage'
            }
        }
    }
}
