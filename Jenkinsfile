pipeline {
    agent any
    environment {
        GITHUB_PAYLOAD = "${params.GITHUB_PAYLOAD}"   
        }
    stages {
        stage("pylint test") {
            steps{
                echo "========= GITHUB ===========  ${GITHUB_PAYLOAD}"
                sh "env"
            }
        }
    }
}

