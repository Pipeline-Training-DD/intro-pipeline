pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
    stage('QA') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
    stage('PROD') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Deepak Dinakaran'
  }
}