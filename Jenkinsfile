@Library('roboshop-shared-library') _

pipeline {
  agent any

  stages {

    // For each commit
    stage('Lint Checks') {
      steps {
        script {
          nodejs.lintChecks()
        }

      }
    }
  } // End of stage
}