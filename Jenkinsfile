pipeline {
    agent any

    stages {
        stage('Checkout & Run') {
            steps {
                sh 'chmod +x test.sh'
                sh './test.sh'
            }
        }
    }
}
