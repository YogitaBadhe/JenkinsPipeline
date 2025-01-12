pipeline {
    agent any
    
    stages {
        stage('Initialize') {
            steps {
                echo 'Initializing Pipeline...'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
        
        stage('Hello World') {
            steps {
                echo 'Hello, World!'
            }
        }
    }
    
    post {
        always {
            echo 'Pipeline execution completed.'
        }
    }
}
