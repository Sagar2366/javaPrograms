pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh "running build "
            }
        }
        stage('Test') { 
            steps {
                echo "running test " 
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploying project" 
            }
        }
    }
}
