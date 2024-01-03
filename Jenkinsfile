pipeline {
  agent any
  stages {
    stage('a') {
      parallel {
        stage('a') {
          steps {
            sh 'a'
          }
        }

        stage('b') {
          steps {
            sh 'b'
          }
        }

      }
    }

    stage('c') {
      steps {
        sh 'c'
      }
    }

  }
}