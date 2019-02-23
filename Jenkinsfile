pipeline {
  agent {
    node {
      label 'remoteHost'
    }

  }
  stages {
    stage('SSH Stage') {
      steps {
        sh 'ssh localhost'
      }
    }
  }
}