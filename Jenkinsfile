pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'docker pull node:latest'
        sh 'npm test'
      }
    }

    stage('deploy') {
      steps {
        sh 'node index.js'
      }
    }

  }
}