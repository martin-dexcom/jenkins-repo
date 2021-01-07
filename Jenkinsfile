pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      parallel {
        stage('Testing A') {
          agent any
          steps {
            echo 'Good morning!'
            sh 'echo "I\'m a ${BUZZ_NAME}"'
          }
        }

        stage('Testing B') {
          steps {
            sleep 5
            echo 'Test B done'
          }
        }

      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
  }
}