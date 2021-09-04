pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "My hello world :P!!!"'
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
