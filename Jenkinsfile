pipeline {
    agent any

    stages {
        stage('Checkout & Verification') {
            steps {
                echo 'Checking workspace directory...'
                sh 'ls -la'
            }
        }

        stage('Test App') {
            steps {
                echo 'Simulating test execution on code pulled from Git...'
                sh 'echo "Code tests passed successfully!"'
            }
        }

        stage('Show Version') {
            steps {
                echo 'Application version:'
                sh 'cat version.txt'
            }
        }

        stage('Deploy Staging') {
            steps {
                echo 'Deploying application to Staging environment...'
            }
        }
    }
}
