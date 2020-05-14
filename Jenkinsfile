pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'chmod +x mvnw && ./mvnw clean install'
            }
        }
    }
}