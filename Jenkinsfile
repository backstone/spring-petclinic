pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dockerNode(image: 'maven:3.5-jdk-8')
        sh 'mvn clean package'
      }
    }
  }
}