pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              echo 'Building..'
              sh 'node -v'
              sh 'npm --version'
              sh 'docker -v'
              sh 'docker compose version'
            }
        }
    }
}