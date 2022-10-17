@Library('roboshop-shared-library@main') _

pipeline {
  agent any

  stages {

    // For each commit
    stage('Lint Checks') {
      steps {
        nodejs.lintChecks()
        }

      }
    }
  } // End of stage
}