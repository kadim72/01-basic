pipeline {
    agent any

    stages {
        stage ('Checkout Code') {
            steps {
                echo "hello"
                checkout scm
                
            }
        }

        stage('Test') {
            steps {
                echo "Jenkinsfile is working"
            }
        }
    }
}
