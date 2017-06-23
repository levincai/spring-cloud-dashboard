pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        parallel(
          "test": {
            sh 'echo "test jsjajsa"'
            
          },
          "Build": {
            sh 'echo "build"'
            
          }
        )
      }
    }
  }
}