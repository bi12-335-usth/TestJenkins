pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'java --version'
                sh 'pwd'
            }
        }
        
        stage('Test') {
            steps {
                sh 'echo "SAY HELLO TO MY LITTLE FRIEND"'
                sh 'echo "MAKE SOME NOISE"'
            }
        }

        stage('Cleanup') {
            steps {
                sh 'echo "Do some push-up, biatch"'
                // Add cleanup commands or scripts here
            }
        }
    }
}