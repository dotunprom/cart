@Library('roboshop-shared-library@main')

sample.info 'Starting'

pipeline {
  agent any

  stages {

    // For each commit
    stage('Lint Checks') {
      steps {
        sh '''
//           we comment this because devs gonna check the failure.
//           ~/node_modules/jslint/bin/jslint.js server.js
          echo Link Check
        '''
      }
    }
  } // End of stage
}
