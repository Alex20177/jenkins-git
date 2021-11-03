pipeline {
    
    agent any

    stages {

        stage('Build') {
        
            steps {
                
                echo "You are in ${env.BRANCH_NAME} branch"
        
            }

        }

        stage('envVars'){

            steps{

                sh "printenv | sort"

            }
        }

    }
}
