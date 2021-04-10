pipeline {
    agent any
    stages {
        stage('first stage') {
            steps {
                git 'https://github.com/jenkinsdemorepo/mavenproject'
                sh 'echo "I am the first stage"'
            }
        }
        stage('second stage') {
            steps {
                sh 'echo "i am the second stage"'
            }
        }
        stage('third stage') {
            steps {
                sh 'echo "I am the third stage"'
            }
        }
        stage('100th stage') {
            steps {
                sh 'echo "I am the third stage"'
            }
        }
        
    }
}
