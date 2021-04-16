pipeline {
  agent any
  stages {
    stage('Built QA') {
      parallel {
        stage('Built QA') {
          steps {
            bat 'echo "run on QA"'
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
