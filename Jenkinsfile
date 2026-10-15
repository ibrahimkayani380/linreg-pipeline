pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker compose down'
                sh 'docker compose pull'
                sh 'docker compose up -d'
            }
        }
    }
}
