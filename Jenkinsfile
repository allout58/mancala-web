pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Install') {
      agent {
        docker {
          image 'cypress/base:10'
        }

      }
      steps {
        sh 'yarn install'
      }
    }
  }
}