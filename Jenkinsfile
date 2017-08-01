pipeline {
  agent any
  stages {
    stage('Prep') {
      steps {
        parallel(
          "Prep": {
            echo 'Prep'
            
          },
          "Build": {
            echo 'Building'
            
          },
          "Result": {
            echo 'Result'
            
          }
        )
      }
    }
  }
}