pipeline {

  agent { docker {image 'node:7-alpine' }}

  stages {

    stage('build') {

      steps {
        sh 'echo building'
        sh 'node --version'
    }

    }
  }
}
