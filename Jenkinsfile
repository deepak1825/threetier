pipeline {
  agent any
  stages {
    stage('frontend') {
      steps {
        sh 'docker build -t mohanraz81/candlfrontend:(${env.BUILD_NUMBER}) frontend'
      }
    }
  }
}