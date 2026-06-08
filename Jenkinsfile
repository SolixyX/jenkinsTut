pipeline {  
    agent any  // "Run this anywhere you have a worker"  
    stages {  
        stage('Build') {  
            steps {  
                echo 'Installing dependencies...'  
                sh 'npm install'  
            }  
        }  
        stage('Test') {  
            steps {  
                echo 'Running tests...'  
                sh 'npm test'  
            }  
        }  
    }  
}  