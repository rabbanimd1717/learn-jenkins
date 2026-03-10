pipeline {
    agent {
       label 'Agent-1' 
    }
    options {
        timeout(time: 1, unit: 'HOURS') 
    }

    stages {
        stage('Build') {
            steps {
                sh 'echo this is build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo this is test'
                sh 'sleep 10'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo this is deploy'
            }
        }
    }
}