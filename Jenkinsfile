pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Build') {
      steps {
        echo 'We are building and committing'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_HOME = 'JDK9'
  }
}