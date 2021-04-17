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
            bat 'run on QA aain'
          }
        }

        stage('Chrome') {
          steps {
            bat 'Run on Chrome'
          }
        }

      }
    }

  }
}