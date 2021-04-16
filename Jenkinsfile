pipeline {
  agent any
  stages {
    stage('Build DEV') {
      parallel {
        stage('Build DEV') {
          steps {
            sh 'echo "run on DEV"'
          }
        }

        stage('Chrome') {
          steps {
            sh 'echo "run on Chrome"'
          }
        }

      }
    }

    stage('Run on QA') {
      parallel {
        stage('Run on QA') {
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

    stage('Run on Stage') {
      steps {
        sh 'echo run on "Stage"'
      }
    }

  }
}