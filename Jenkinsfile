pipeline {
    agent any

    stages {
        stage('Read Version') {
            steps {
                echo 'Reading version from file...'
                sh 'cat version.txt'
            }
        }
    }
}
