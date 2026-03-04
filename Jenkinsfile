pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                bat 'mvn compile'
                echo 'Initiating compilation'
            }
        }
        stage('execution') {
            steps {
                bat 'java-project2-1.6.jar'
            }
        }
    }
}
