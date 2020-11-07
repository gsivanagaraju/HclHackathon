pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                withMaven(maven : 'apache-maven-3.6.1') {
                sh'mvn clean compile'
                }
                echo 'Build success..'
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