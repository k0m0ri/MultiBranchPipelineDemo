pipeline {
    agent any
    stages {
        stage('Cleanup Workspace') {
            steps {
                cleanWs()
                echo "Cleaned Up Workspace For Project"
            }
        }
        
        stage('Code Checkout') {
            steps {
                echo "Code Checkout"
            }
        }

        stage('Unit Testing') {
            steps {
                echo "Runnung Unit Tests"
            }
        }

        stage('Code Analysis') {
            steps {
                echo "Running Code Analysis"
            }
        }
    }
}