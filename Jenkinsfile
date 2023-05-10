pipeline {
  agent any
  stages {
    stage('Pipeline Stages'){
      steps {
        sh "touch hi.sh"
        sh "echo 'echo 123' > hi.sh"
      }
   }
    stage('second stage'){
      steps {
        
        sh "mv hi.sh /var/lib/yellow"
        sh "chmod +x /var/lib/yellow/hi.sh"
        sh "sh /var/lib/yellow/hi.sh"
      }
    }
  }
}
