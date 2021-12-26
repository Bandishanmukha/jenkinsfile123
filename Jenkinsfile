pipeline {
  agent any
  stages {
     stage('Jenkinsfile') {
        steps{
           sh "ls -la"
           sh "cat Jenkinsfile"
           sh "chmod 700 ./script.sh"
           sh "sudo ./script.sh"
        }
     }
     stage('jenkinsfile') {
        steps{
           sh "ls -la"
           sh "cat jenkinsfile"
           sh "pwd"
        }
     }
  }
}  
