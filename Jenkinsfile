pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                bat 'mvn compile'
                echo 'build process initiated'
            }
            stage('execute') {
            steps {
                bat 'java -jar demo.jar'
                echo 'execution done'
            }
        }
    }
}
