pipeline {
  agent any
  stages {
    stage('git pull') {
      steps {
        sh 'echo "hello"'
      }
    }

    stage('unit cases') {
      steps {
        sh 'npm test'
      }
    }

  }
}