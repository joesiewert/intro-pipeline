pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Yo ${MY_NAME}!'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Joe'
  }
}