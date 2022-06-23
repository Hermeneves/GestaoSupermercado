pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                git'https://github.com/Hermeneves/GestaoSupermercado.git'
                bat'.mvnw clean compile'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                
            }
        }
        stage('Deploy') {
            steps {
                echo 'Testing...'
            }
        }
    }
}
