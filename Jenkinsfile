pipeline {
  agent any
  stages {
    stage('Build DEV') {
      parallel {
        stage('Build DEV') {
          steps {
            sh 'echo "Run on DEV"'
          }
        }

        stage('Chrome') {
          steps {
            sh 'echo "run on chrome"'
          }
        }

      }
    }

  }
}