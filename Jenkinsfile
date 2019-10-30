pipeline {
    agent { docker { image 'golang:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'ls -a'
                sh 'go version'
            }
        }
    }
}
