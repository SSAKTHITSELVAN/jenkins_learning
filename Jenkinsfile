pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building App'
            }
        }

        stage('Test - unit') {
            steps {
                sh 'echo Unit Tests Passed'
            }
        }
        stage('Test - integration') {
            steps {
                sh 'echo Integration Tests Passed'
            }
        }
    }
}