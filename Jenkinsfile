pipeline {
  agent any
  stages {
    stage('Pipeline Stages'){
      steps {
        sh "touch hi.txt"
        sh "echo 'echo "Hiya!!!!!!!"' " > hi.txt
      }
   }
    stage('second stage'){
      steps {
        sh "mkdir yellow"
        sh "mv hi.txt yellow"
