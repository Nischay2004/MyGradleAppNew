pipeline {
  agent any
  tools {
    gradle 'Gradle'
    jdk 'JDK'
  }
  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/Nischay2004/MyGradleAppNew.git'
      }
    }
    stage('Build') {
      steps {
        sh './gradlew build'
      }
    }
  }
}
