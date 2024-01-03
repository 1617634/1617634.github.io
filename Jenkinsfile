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
        sh 'echo "Hello, World!a"'
      }
    }

    stage('d') {
      steps {
        sh 'echo "Hello, World!a"'
      }
    }

    stage('e') {
      steps {
        sh 'echo "Hello, World!a"'
      }
    }

  }
}