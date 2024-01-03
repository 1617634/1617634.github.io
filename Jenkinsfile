pipeline {
  agent any
  stages {
    stage('a') {
      parallel {
        stage('a') {
          steps {
            sh 'echo "Hello, World!a"'
          }
        }

        stage('b') {
          steps {
            sh 'echo "Hello, World!b"'
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