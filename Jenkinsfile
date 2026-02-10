pipeline {
    agent {
        docker {
            image 'alpine:latest'
            args '-u root'
        }
    }

    stages {
        stage('Docker Test') {
            steps {
                sh 'echo "Hello from Docker"'
                sh 'uname -a'
                sh 'cat /etc/os-release'
            }
        }
    }
}
