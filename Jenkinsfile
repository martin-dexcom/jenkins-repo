pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      agent any
      steps {
        echo 'Good morning!'
        junit '**/surefire-reports/**/*.xml'
      }
    }

  }
}