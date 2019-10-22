pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               sh "docker-compose up --abort-on-container-exit"
            }
        }
    }
}