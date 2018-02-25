pipeline {
    agent { 
        label 'Nodejs_slave1'}
    stages {
        stage('Test') {
            agent { dockerfile true }
            steps {
                sh 'node --version'
                sh 'mvn --version'
            }
        }
    }
}
