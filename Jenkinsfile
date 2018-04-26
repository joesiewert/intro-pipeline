pipeline {
  agent {
    node {
      label 'jdk9'
    }
    
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Yo!'
        sh 'java -version'
      }
    }
  }
}