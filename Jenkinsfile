/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:20.11.1-alpine3.19' } }
    stages {
        stage('build') {
            steps {
                echo "Building..."
                sh 'node --version'
            }
        }
    }
}
