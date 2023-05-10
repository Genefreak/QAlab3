pipeline {
  agent any
  stages {
    stage('Pipeline Stages'){
      steps {
        sh "touch hi.sh"
        sh "echo 'echo 123' " > hi.sh
      }
   }
    stage('second stage'){
      steps {
        sh "mkdir yellow"
        sh "mv hi.sh yellow"
        sh "sh /yellow/hi.sh"
      }
    }
  }
}
