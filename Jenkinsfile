pipeline {
    agent any
    stages {
        stage("pylint test") {
            steps{
                echo "======= start ======="
                sh """ls -la
                      env
                      echo "$GIT_COMMIT"
                      cat *.py"""

            }
        }
    }
}

