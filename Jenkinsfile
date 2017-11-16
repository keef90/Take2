pipeline {
  agent any
  stages {
    stage('Initial Script Build') {
      parallel {
        stage('Initial Script Build') {
          steps {
            sh 'echo %username%'
          }
        }
        stage('Hello world') {
          steps {
            echo 'Hello world'
          }
        }
      }
    }
  }
}