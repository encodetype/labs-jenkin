pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''npm test
'''
      }
    }

    stage('deploy') {
      steps {
        sh 'node index.js'
      }
    }

  }
}