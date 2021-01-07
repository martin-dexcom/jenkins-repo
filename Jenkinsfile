pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      agent any
      steps {
        echo 'Good morning!'
        archiveArtifacts(artifacts: 'target/*jar', fingerprint: true)
      }
    }

  }
}