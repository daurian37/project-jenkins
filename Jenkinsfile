pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'building'
                bat 'npm install' 
            }
        }

        stage('Test') {
            steps {
                echo 'testing'
                bat 'npm test'
            }
        }

         stage('Deploy / Delivery') {
            steps {
                echo 'deploying' 
            }
        }

    }      
}