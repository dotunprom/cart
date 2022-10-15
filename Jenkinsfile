pipeline {
  agent any

  stages {
    // For each commit
    stage( 'Lint Checks') {
      steps {
        sh '''
          ~/node_modules/bin/jslint.js server.js
        '''
      }
    }
  } // End of stage
}
