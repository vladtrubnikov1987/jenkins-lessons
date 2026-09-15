pipeline {
    agent any

    stages {
        stage('Read Version') {
            steps {
                script {
                    def version = sh(
                        script: 'cat version.txt',
                        returnStdout: true
                    ).trim()

                    echo "Base version: ${version}"
                    echo "Dynamic version: ${version}-build-${BUILD_NUMBER}"
                }
            }
        }
    }
}
