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

        stage('Stage') {
          steps {
            sh 'mvn --version'
          }
        }

      }
    }

  }
}