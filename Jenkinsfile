pipeline {
    agent none
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'chris'
                }
            }
            steps {
                echo hello
            }
        }
    }
}