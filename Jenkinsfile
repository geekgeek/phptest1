pipeline {
  agent {
    docker {
      image 'php'
    }

  }
  stages {
    stage('error') {
      steps {
        sh '/var/run/docker.sock version'
      }
    }
  }
}