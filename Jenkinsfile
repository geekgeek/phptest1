pipeline {
  agent {
    docker {
      image 'php:7.0-apache'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'docker-compose up'
      }
    }
  }
}