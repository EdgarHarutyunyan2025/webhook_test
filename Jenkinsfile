pipeline {
    agent any
    stages {
        stage("pylint test") {
            steps{
                script {
                    def payload = request.payload
                    echo "Received GitHub webhook payload: ${payload}"
                }    
            }
        }
    }
}

