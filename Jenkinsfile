pipeline {
    agent any

    stages {
        stage('Info') {
            steps {
                sh 'echo "Running on Jenkins"'
                sh 'uname -a'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Build step"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Test step"'
            }
        }
    }
}
