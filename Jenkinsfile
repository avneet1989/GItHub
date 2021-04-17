pipeline {
  agent any
  stages {
    stage('Built QA') {
      parallel {
        stage('Built QA') {
          steps {
            bat 'echo run on QA'
          }
        }

        stage('Chrome') {
          steps {
            bat 'echo run on chrome'
          }
        }

      }
    }

    stage('QA') {
      parallel {
        stage('QA') {
          steps {
            bat 'echo run on QA again'
          }
        }

        stage('Chrome') {
          steps {
            bat 'echo Run on Chrome'
          }
        }

      }
    }

  }
}