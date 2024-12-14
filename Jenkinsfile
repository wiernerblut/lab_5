pipeline {
    agent any
    stages {
        stage('Lint') {
            steps {
                sh 'npm install'
                sh 'eslint index.js || true'
            }
        }
    }
}
