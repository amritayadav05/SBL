pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Compiling Java project......'
                bat 'javac HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                echo 'Running the application......'
                bat 'java HelloWorld'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application......'
                echo 'Application deployed successfully!'
            }
        }
    }
}
