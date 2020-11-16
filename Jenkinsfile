

echo 'Begin'

pipeline {
    agent { none }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'npm start'
            }
        }
    }
}