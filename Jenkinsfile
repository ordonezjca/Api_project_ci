

echo 'Begin'

pipeline {
    agent { any }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'npm start'
            }
        }
    }
}