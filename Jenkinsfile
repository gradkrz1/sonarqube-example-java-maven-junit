pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn install'
        echo 'Jest supcio'
      }
    }
    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }
  }
}