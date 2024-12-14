pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                branch 'main'
            }
            steps {
                sh 'echo Building on main branch'
            }
        }
        stage('Test') {
            when {
                branch 'dev'
            }
            steps {
                sh 'echo Testing on dev branch'
            }
        }
    }
}
