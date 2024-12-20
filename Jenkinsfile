pipeline {
    agent any
    environment {
        GITHUB_REF = "${params.ref}"   
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

