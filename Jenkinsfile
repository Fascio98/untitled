pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            sh 'mvn clean test'
          }
        }

        stage('Stage2') {
          steps {
            sh 'mvn --version'
          }
        }

      }
    }

  }
}