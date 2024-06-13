#!groovy
pipeline {
   agent none
   stages {     
    stage('Maven Install') {
      agent {         
       docker {          
         image 'maven:latest'         
     }       
  }       
  steps {
       echo "ciao"
       sh 'mvn clean install'
       echo "prova"
       }
     }
   }
 }
