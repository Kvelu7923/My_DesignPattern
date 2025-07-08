pipeline {
    agent any
    triggers {
        cron('H * * * *')
    }
    stages {
        stage('Build & Test') {
            steps {
                echo 'Running Tests...'
                bat 'mvn clean test'   // For Windows Jenkins agents
            }
        }
    }
}
