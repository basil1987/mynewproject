pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                ant build.xml
            }
        }
        stage('Deploy') { 
            steps {
                echo "Hello world" 
            }
        }
    }
}

