pipeline {
  agent any
  stages {
    stage('dockerfile') {
      steps {
        sh 'dotnet build'
      }
    }
  }
}