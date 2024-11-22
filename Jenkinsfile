pipeline {
    agent any

    stages {
        stage ('Checkout Code') {
            steps {
                echo "hello"
                sh 'git clone https://github.com/kodekloudhub/jenkins-project.git'
                
            }
        }

        stage('Test') {
            steps {
                echo "Jenkinsfile is working"
            }
        }
    }
}
