pipeline {
  agent any
  stages {
    stage('Buzz bild') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

    stage('buzz test') {
      steps {
        sh './jenkins/build.sh'
      }
    }

  }
}