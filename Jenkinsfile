#!groovy
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Hello, BUild Phase."
                git 'https://github.com/dhgautam/helloworldjava.git'
                checkout scm
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Deploy') {
            steps {
                echo "Hello, deploy Phase."
            }
        }
        stage('Test') {
            steps {
                echo "Hello, Test Phase."
            }
        }
        
    }
}
