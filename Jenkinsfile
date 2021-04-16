pipeline {
  agent any
  stages {
    stage('Build DEV') {
      parallel {
        stage('Build DEV') {
          steps {
            bat 'echo "Run on DEV"'
          }
        }

        stage('Chrome') {
          steps {
            bat 'echo "run on chrome"'
          }
        }

      }
    }

  }
}
