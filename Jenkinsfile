@Library('roboshop-shared-library@main') _

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