pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                // git url: 'https://github.com/aklymov13/devtest1.git'
                sh 'chmod +x devtest1.sh'
            }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh './devtest1.sh'
            }
        }
        }
    }
}
