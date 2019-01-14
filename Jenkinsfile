pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''
mvn clean install'''
      }
    }
  }
}