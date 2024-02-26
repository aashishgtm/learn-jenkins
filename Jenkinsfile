pipeline {
    agent any   
    stages {
        stage("build") {
            echo 'Starting the build process .....'
            sh 'npm install'
            sh 'npm build'
        }
        stage("deploy") {
            echo 'Starting the deploy process .....'
            sh 'npm start'
        }
    }
}