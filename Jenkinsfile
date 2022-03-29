pipeline {
  agent any
  stages {
    stage('1') {
      parallel {
        stage('1') {
          steps {
            sh 'echo "hello world1"'
          }
        }

        stage('2') {
          steps {
            sh 'echo "hello world2"'
          }
        }

      }
    }

    stage('3') {
      parallel {
        stage('3') {
          steps {
            sh 'echo \'hello world3\''
          }
        }

        stage('4') {
          steps {
            sh 'echo \'hello world4\''
          }
        }

      }
    }

  }
}