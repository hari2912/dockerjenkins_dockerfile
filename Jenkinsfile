pipeline {
    agent { 
        label 'Nodejs_slave1'}
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'mvn --version'
            }
        }
    }
}
