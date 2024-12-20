pipeline {
    agent any
    environment {
        GITHUB_PAYLOAD = "${params.GITHUB_PAYLOAD}"   
        }
    stages {
        stage("pylint test") {
            steps{
                    sh "echo $GITHUB_PAYLOAD" 
                    sh "env"
            }
        }
    }
}

