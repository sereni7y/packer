pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'packer --version'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
