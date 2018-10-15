pipeline {
  agent none
  stages {
    stage('dockerfile') {
      steps {
        sh 'docker build -t dockerci'
      }
    }
  }
}