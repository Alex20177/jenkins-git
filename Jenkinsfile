pipeline {
    
    agent any

    stages {

        stage('Build') {
        
            steps {
                
                writeFile file: 'test-result.txt' , text : 'Passed'
                archiveArtifacts 'test-result.txt'
        
            }

        }

    }

    post{
        success{
            echo 'Sending email confirmation ...!!!'
        }
    }
}
