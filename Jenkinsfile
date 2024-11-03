pipeline {
    agent { docker { image 'gradle:8.4-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'gradle --version'
            }
        }
    }
}
