pipeline {
    agent any
    triggers {
        cron('H * * * *')  // Runs every hour
    }
    stages {
        stage('Example') {
            steps {
                echo 'Running every hour from GitHub Pipeline...'
            }
        }
    }
}
