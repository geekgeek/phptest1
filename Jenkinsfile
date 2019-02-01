pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''git clone https://github.com/geekgeek/phptest1.git
'''
        sh 'docker-compose up'
      }
    }
  }
}