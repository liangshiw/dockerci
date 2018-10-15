pipeline {
  agent any
  stages {
    stage('dockerfile') {
      steps {
        sh 'docker build -t dockerci'
      }
    }
  }
}