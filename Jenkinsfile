pipeline {
  agent {
    docker {
      image 'cypress/base:10'
    }

  }
  stages {
    stage('Install') {
      steps {
        sh 'yarn install'
      }
    }
  }
}
