pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add build steps here
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Add test steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment steps here
            }
        }
    }
    post
    {
        always
        {
            emailext body: 'I\'m here', subject: 'my 2nd', to: '24caratsugar@gmail.com'
        }
    }
}
