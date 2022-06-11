pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '''-p 3030:3000
-p 4040:4000'''
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