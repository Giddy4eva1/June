pipeline {
  agent any
  stages {
    stage('Source') { // Get code
      steps {
        echo 'a short message'
        }
    }
    
    stage('Compile') { // Compile and do unit testing
      steps {
        echo 'trying'
      }
      steps {
        // run Gradle to execute compile and unit testing
        echo 'gradle clean compileJava test'
      }
    }
  }
}
