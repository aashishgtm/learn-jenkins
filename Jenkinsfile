pipeline {
    agent any   
    stages {
        stage("build") {

            steps{
                echo 'Starting the build process .....'
                sh 'npm install'
                sh 'npm build'
            }
        }
        stage("deploy") {
            
            steps{
                echo 'Starting the deploy process .....'
                sh 'npm start'
            }
        }
    }
}