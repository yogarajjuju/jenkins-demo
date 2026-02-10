pipeline {
    agent any

    stages {
        stage('Docker test') {
            steps {
                sh '''
                  docker run --rm alpine:latest \
                  sh -c "echo Hello from Docker && uname -a"
                '''
            }
        }
    }
}
