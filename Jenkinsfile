pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Yo!'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Joe'
  }
}