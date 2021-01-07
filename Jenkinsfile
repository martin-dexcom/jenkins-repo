pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      agent any
      steps {
        echo 'Good morning!'
        sh 'echo "I\'m a ${BUZZ_NAME}"'
      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
  }
}