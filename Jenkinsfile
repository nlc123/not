pipeline {
  agent any
  stages {
    stage('check version') {
      parallel {
        stage('check version') {
          steps {
            sh 'npm -v'
          }
        }

        stage('check package json file') {
          steps {
            fileExists 'package.json'
          }
        }

      }
    }

    stage('build NOT app') {
      steps {
        sh 'npm run build'
      }
    }

  }
}