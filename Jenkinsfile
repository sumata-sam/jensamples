pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "build"
                sh 'pwd'
            }
        }
        stage('Test') { 
            steps {
                 echo "test"
                sh 'whoami'
            }
        }
        stage('Deploy') { 
            steps {
                 echo "deploy"
                sh 'uptime'
            }
        }
    }
}

