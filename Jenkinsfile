pipeline {
    agent any

    stages {
        stage('Info') {
            steps {
                sh '''
                  echo "=== INFO STAGE ==="
                  whoami
                  pwd
                  echo "Shell:"
                  echo $SHELL
                  uname -a
                '''
            }
        }

        stage('Build') {
            steps {
                sh 'echo "=== BUILD STAGE DONE ==="'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "=== TEST STAGE DONE ==="'
            }
        }
    }
}
