pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '/vagrant/packer --version'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
