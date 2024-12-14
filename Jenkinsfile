pipeline {
    agent any
    stages {
        stage('Print Branch Info') {
            steps {
                sh 'echo Current branch is $BRANCH_NAME'
            }
        }
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
