pipeline {
  agent any
  stages {
    stage('Check package json') {
      steps {
        fileExists 'package.json'
      }
    }

    stage('Verify tool versions') {
      steps {
        sh '$npm --version'
      }
    }

  }
}