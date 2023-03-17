// Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { kubernetes }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}