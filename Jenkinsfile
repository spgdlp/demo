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
        bat 'javac /src/main/java/first_app/app.java'
      }
    }
	stage('execute') {
      steps {
        bat 'java /src/main/java/first_app/app.java'
      }
    }
  }
}
