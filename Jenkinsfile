pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        parallel(
          "Build": {
            sh '''#/bin/bash

echo "Tigoddiri"'''
            echo 'Tigoddiri'
            
          },
          "": {
            echo 'Parallel Step'
            
          }
        )
      }
    }
    stage('') {
      steps {
        echo 'Done'
      }
    }
  }
}