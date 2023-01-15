pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'mkdir abc'
                sh 'ls -lart'
                sh 'pwd'
            }
        }
      
      stage('Hello1') {
            steps {
                echo 'Hello World'
                sh 'rmdir abc'
               // sh 'ls -lart'
                sh 'pwd'
            }
        }
      
    }
}
