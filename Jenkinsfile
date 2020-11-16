

echo 'Begin'

pipeline {
    agent { 'First agent' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'npm start'
            }
        }
    }
}