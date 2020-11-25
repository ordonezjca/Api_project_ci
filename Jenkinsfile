

echo 'Begin'

pipeline {
    agent { label "include" && "!exclude" }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('Initialize') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }
}