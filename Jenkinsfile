pipeline {
  agent any
  stages {
    stage('Stage1-DEMO') {
      parallel {
        stage('Stage1-DEMO') {
          steps {
            sh 'echo Hello Wold'
            sh 'echo STEP2'
          }
        }
        stage('Stage1-DEMO1') {
          steps {
            sh 'echo Hello'
          }
        }
      }
    }
    stage('Stage2-Demo') {
      steps {
        sh 'echo hello'
      }
    }
  }
}