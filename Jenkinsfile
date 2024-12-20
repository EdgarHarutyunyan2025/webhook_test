pipeline {
    agent any
    environment {
        GITHUB_REF = "${params.default_branch}"   
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

