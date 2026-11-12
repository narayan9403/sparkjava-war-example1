pipeline {
  agent any
  environment {
    path = "/optmaven/bin:$PATH"
  }
  stages {
    stage('build') {
      stage {
        sh 'mvn clean package'
      }
    }
  }
}
