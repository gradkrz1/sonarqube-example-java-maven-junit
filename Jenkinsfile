pipeline {
  agent any
  stages {
    stage('Compile') {
      parallel {
        stage('Compile') {
          steps {
            sh 'mvn install'
            echo 'Jest supcio'
          }
        }
        stage('') {
          steps {
            echo 'Hello'
          }
        }
      }
    }
    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }
  }
}