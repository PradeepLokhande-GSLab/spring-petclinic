#!groovy

pipeline {
  agent none
    stage('Docker Build') {
      agent any
      steps {
        sh 'docker build -t PradeepLokhande-GSLab/spring-petclinic:latest .'
      }
    }
  }
}
