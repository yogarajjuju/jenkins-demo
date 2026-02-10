pipeline {
    agent {
        docker {
            image 'alpine:latest'
            args '-u root'   // avoids permission issues
        }
    }

    stages {
        stage('Test in Docker') {
            steps {
                sh 'echo "Hello from Docker"'
                sh 'uname -a'
                sh 'cat /etc/os-release'
            }
        }
    }
}
