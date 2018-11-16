pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'ls -lah'
          }
        }
        stage('') {
          steps {
            echo 'running'
          }
        }
      }
    }
  }
}