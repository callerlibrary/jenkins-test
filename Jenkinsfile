pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              echo 'Building..'
              sh 'npm --version'
              sh 'docker -v'
              sh 'docker compose version'
            }
        }
    }
}