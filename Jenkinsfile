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
        bat(script: 'npm --version', returnStatus: true, returnStdout: true)
      }
    }

  }
}