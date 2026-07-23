pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/your-username/Day67_Ansible_Advanced.git'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                ansible-playbook \
                -i inventory \
                site.yml
                '''
            }
        }
    }
}
