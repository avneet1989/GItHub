pipeline {
  agent any
  stages {
    stage('Built QA') {
      parallel {
        stage('Built QA') {
          steps {
            sh 'echo "run on QA"'
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