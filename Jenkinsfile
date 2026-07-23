 pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/manichandana17/Day67_Ansible_Advanced.git'
            }
        }

        stage('Verify Files') {
            steps {
                bat 'dir'
            }
        }
    }
}


