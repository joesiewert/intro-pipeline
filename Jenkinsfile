pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo "Yo ${MY_NAME}!"
        sh 'java -version'
      }
    }
    stage('Deploy') {
      input {
        message 'Should we continue?'
      }
      steps {
        echo 'Continuing with deployment'
      }
    }
  }
  environment {
    MY_NAME = 'Joe'
  }
}