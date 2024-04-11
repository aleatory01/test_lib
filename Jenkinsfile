@Library ('shared_lib')_
pipeline {
  agent any

  stages {
    stage ( 'Build' ) {
      steps {
        script {
          build ()
        }
      }
    }
    stage ( 'Deploy' ) {
      steps {
        script {
          deploDemo()
        }
      }
    }
  }
}
