pipeline {
    agent {
        label 'dev'
    }
    options {
        timeout(time: 30, unit: 'MINUTES')
        disableConcurrentBuilds()
    }
    stages {
        stage('Build') { 
            steps {
                sh 'echo This is Build'
                sh 'sleep 5'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo This is Test'
                
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo This is Deploy'
            }
        }
    }
}