pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                mvn clean
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}