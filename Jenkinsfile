pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh ant
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo "Hello world"'
            }
        }
    }
}

