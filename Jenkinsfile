pipeline {
    agent any

    stages {
        stage ('Checkout Code') {
            steps {
                echo "hello"
                sh 'rm -rf ./jenkins-project' || true
                sh 'git clone https://github.com/kodekloudhub/jenkins-project.git'
                
            }
        }
    }
}
