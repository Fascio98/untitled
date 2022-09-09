pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            bat 'mvn clean test'
          }
        }

        stage('Stage2') {
          steps {
            bat 'mvn --version'
          }
        }

      }
    }

  }
}