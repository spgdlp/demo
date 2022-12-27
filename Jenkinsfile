pipeline {
  agent any
  stages {
    stage('java version') {
      steps {
        bat 'java --version'
      }
    }
    stage('compile') {
      steps {
        bat 'javac app.java'
      }
    }
	stage('execute') {
      steps {
        bat 'java app.java'
      }
    }
  }
}