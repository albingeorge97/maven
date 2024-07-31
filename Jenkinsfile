pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'building the application'
            }
        }
        
        stage('Test') {
            steps {
                echo 'testing the application'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'deploy the application'
            }
        }
    }
    
    post
    {
        always
        {
            emailext body: 'qwertyuiosdfghjk', subject: 'pipeline', to: 'albinbsoft4448@gmail.com'
        }
    }
}
