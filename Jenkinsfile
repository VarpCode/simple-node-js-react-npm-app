pipeline {
  agent {
    docker {
      args '''-p 3030:3000
-p 4040:4000'''
      image 'node:18-alpine3.15'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}