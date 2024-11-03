/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'gradle:8.10.2-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'gradle --version'
            }
        }
    }
}
