pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        parallel(
          "Build": {
            echo 'Tigoddiri'
            
          },
          "error": {
            echo 'Parallel Step'
            
          }
        )
      }
    }
    stage('error') {
      steps {
        echo 'Done'
      }
    }
  }
}