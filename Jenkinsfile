pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
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