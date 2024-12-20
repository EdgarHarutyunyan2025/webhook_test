pipeline {
    agent any
    environment {
        GITHUB_PAYLOAD = "${params.GITHUB_PAYLOAD}"   
        }
    stages {
        stage("pylint test") {
            steps{
                echo "Payload: ${params}"
                sh "env"
            }
        }
    }
}

