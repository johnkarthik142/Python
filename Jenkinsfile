pipeline {
    agent any 
    
    stages {
        stage('Version') {
            steps {
                sh 'python3 --version'
            }
        } 
        stage('Build') {
            steps {
                sh 'python3 add.py'
            }
        }
        
        
        
    }
}
