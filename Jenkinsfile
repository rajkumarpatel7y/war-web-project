pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'date'
                sh 'pwd'
            }
        }    
            
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }  
         
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }  
    }
}
