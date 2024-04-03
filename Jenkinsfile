pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'building'
                sh 'npm install' 
            }
        }

        stage('Test') {
            steps {
                echo 'testing'
                sh 'npm test'
            }
        }

         stage('Deploy / Delivery') {
            steps {
                echo 'deploying' 
            }
        }

    }      
}