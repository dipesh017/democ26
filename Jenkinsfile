pipeline {
  agent any
  stages {
    stage('git pull') {
      steps {
        sh 'echo "hello"'
      }
    }

    stage('unit cases') {
      parallel {
        stage('unit cases') {
          steps {
            sh 'npm test'
          }
        }

        stage('windows testing') {
          steps {
            sleep 3
          }
        }

      }
    }

  }
}