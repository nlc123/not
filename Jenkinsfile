pipeline {
  agent any
  stages {
    stage('check version') {
      steps {
        sh 'npm -v'
      }
    }

    stage('build NOT app') {
      steps {
        sh 'npm run build'
      }
    }

  }
}