pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        bat(script: 'mvn clean test', returnStatus: true, returnStdout: true)
      }
    }

  }
}