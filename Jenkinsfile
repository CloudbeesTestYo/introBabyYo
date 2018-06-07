pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'What up!'
        sh 'java -version'
      }
    }
  }
}