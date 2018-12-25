pipeline {
  agent {
    docker {
      image 'ubuntu:latest'
      args 'apt-get update'
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