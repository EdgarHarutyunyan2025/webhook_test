pipeline {
    agent any
    stages {
        stage("pylint test") {
            steps{
                script {
                    def payload = $payload
                    echo "Received GitHub webhook payload: ${payload}"
                }    
            }
        }
    }
}

