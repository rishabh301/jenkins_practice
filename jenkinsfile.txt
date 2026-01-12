pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo "build step is successful"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploy step is successful"
            }
        }
        stage('Test') {
            steps {
                echo "test step is successful"
            }
        }
        stage('Release') {
            steps {
                echo "release step is successful"
            }
        }
    }
}
