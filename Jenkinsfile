pipeline {
    agent any 
    stages {
        stage('clone repo') { 
            steps {
                sh "git clone https://github.com/Sagar2366/javaPrograms.git"
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
