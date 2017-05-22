pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        parallel(
          "Build": {
            echo 'Tigoddiri'
            
          },
          "Parallel Build": {
            echo 'Parallel Step'
            
          }
        )
      }
    }
    stage('Finalise') {
      steps {
        echo 'Done'
      }
    }
  }
}