pipeline {
  agent any
  stages {
    stage('1') {
      parallel {
        stage('1') {
          steps {
            bat(script: '1.bat', encoding: 'utf-8', label: '1', returnStatus: true, returnStdout: true)
          }
        }

        stage('2') {
          steps {
            bat(script: '2.bat', encoding: 'utf-8', label: '2', returnStatus: true, returnStdout: true)
          }
        }

      }
    }

  }
}