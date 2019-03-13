pipeline {
    agent { docker { image 'node:10.15' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'node --version'
                sh 'nvm --version'
                sh 'echo Hello Jenkins'
            }
        }
    }
}