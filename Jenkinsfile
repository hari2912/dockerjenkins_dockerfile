pipeline {
    agent { 
        label 'Nodejs_slave1'
        dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'mvn --version'
            }
        }
    }
}
