pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Bonjour World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
