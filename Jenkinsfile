pipeline {
    agent { 
        label 'Nodejs_slave1'}
    stages {
        agent { dockerfile true }
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'mvn --version'
            }
        }
    }
}
