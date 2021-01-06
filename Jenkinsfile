pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      agent any
      steps {
        echo 'Bees Buzz!'
      }
    }

    stage('Bees Bees') {
      agent any
      steps {
        echo 'Buzz, Bees, Buzz! '
        echo 'Bees Buzzing! '
      }
    }

    stage('Bees Deploy') {
      steps {
        echo 'The bees are now deploying'
        sleep 5
        sh 'echo "Amazing what can be done with Jenkins"'
      }
    }

  }
}