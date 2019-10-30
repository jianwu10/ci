pipeline {
    agent { docker { image 'buildbot:2.5.2' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
                sh 'ls'
                sh 'cd tools'
                sh 'ls'
            }
        }
    }
}
