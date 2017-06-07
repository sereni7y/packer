pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '/vagrant/packer --version'
                sh '/vagrant/packer validate '
                sh '/vagrant/packer build '
            }
        }
    }
}
