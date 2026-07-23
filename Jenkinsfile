pipeline {
    agent any

    stages {

        stage('Verify Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Show Git Status') {
            steps {
                bat 'git status'
            }
        }
    }
}
