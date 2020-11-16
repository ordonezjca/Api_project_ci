

echo 'Begin'

pipeline {
    agent { label "include" && "!exclude" }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'npm start'
            }
        }
    }
}