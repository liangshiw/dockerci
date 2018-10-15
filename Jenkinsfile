pipeline {
  agent {
    docker {
      image 'dockerci'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'dotnet build'
      }
    }
  }
}