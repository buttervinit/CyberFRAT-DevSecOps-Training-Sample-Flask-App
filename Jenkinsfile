pipeline {
  agent any
  
  stages {
    stage('Build Docker Image') {
      steps {
        sh 'dcoker build -t cyberfrat:$BUILD_NUMBER .'
       }
    }
  }
 }
