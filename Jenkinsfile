pipeline {
    agent any

    stages {
        stage('Check out') {
            steps {
                 git branch: 'main', credentialsId: 'ID', url: 'https://github.com/<username>/<repo>.git'
                 sh 'ls'
                 sh 'git branch'
            }
            
        }
        stage('the end') {
            steps {
                echo 'Thanks'                 
            }            
        }
    }
}

