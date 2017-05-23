pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        parallel(
          "Build": {
            echo 'Tigoddiri'
            
          },
          "SP2010": {
            echo 'SP2010'
            
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