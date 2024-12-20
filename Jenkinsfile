pipeline {
    agent any
    environment {
        GITHUB_REF = "${params.GITHUB_REF}"   
        }
    stages {
        stage("pylint test") {
            steps{
                    sh "echo $GITHUB_REF" 
                    sh "env"
            }
        }
    }
}

