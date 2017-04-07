pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'test shell'
      }
    }
  }
  environment {
    testName = 'value'
  }
}