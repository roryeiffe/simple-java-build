pipeline {
  agent { docker { image 'maven:3.9.6-eclipse-temurin-17-alpine'} }
  stages {
    stage('Build') {
      sh 'mvn -v'
    }
  }
}