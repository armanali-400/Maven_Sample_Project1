pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                bat 'mvn compile'
                echo 'build process initiated'
            }
            
            stage('test') {
            steps {
                bat 'mvn test'
                echo 'Test process initiated'
            }
            stage('deploy') {
            steps {
                bat 'mvn deploy'
                echo 'deploy process initiated'
            }
        }
    }
}
