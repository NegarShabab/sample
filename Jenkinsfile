pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'npm install'
          }
        }
        stage('Start') {
          steps {
            sh 'npm start'
          }
        }
      }
    }
  }
}