pipeline {
  agent {
    docker {
      image 'php'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'docker version'
      }
    }
  }
}