pipeline {
  agent any
  stages {
    stage('Check package json') {
      steps {
        fileExists 'package.json'
      }
    }

  }
}