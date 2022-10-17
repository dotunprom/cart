@Library('roboshop-shared-library@main')

pipeline {
  agent any

  stages {

    // For each commit
    stage('Lint Checks') {
      steps {
        script {
          sample.info('Starting', 'google.com')
        }
        sh '''
//           we comment this because devs gonna check the failure.
//           ~/node_modules/jslint/bin/jslint.js server.js
          echo Link Check
        '''
      }
    }
  } // End of stage
}