pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh 'npm install'
        sh 'npm install -g bower'
        sh 'bower install'
        sh 'gulp'
      }
    }
  }
}