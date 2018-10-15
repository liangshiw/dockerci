pipeline {
  agent {
    docker {
      image 'dockerci'
    }

  }
  stages {
    stage('dockerfile') {
      steps {
        sh 'docker build -t dockerci'
      }
    }
  }
}