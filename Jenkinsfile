pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '/vagrant/packer --version'
                sh '/vagrant/packer validate nginx.json'
                sh '/vagrant/packer build nginx.json'
            }
        }
    }
}
