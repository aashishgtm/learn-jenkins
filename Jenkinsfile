pipeline {
    agent any   
    stages {
        stage("build") {
            when {
                expression {
                    BRANCH_NAME == 'master'
                }
            }

            steps{
                echo 'Starting the build process .....'
                // sh 'npm install'
                // sh 'npm build'
            }
        }
        stage("deploy") {

            steps{
                echo 'Starting the deploy process .....'
                // sh 'npm start'
            }
        }
    }
}