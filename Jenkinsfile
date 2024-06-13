#!groovy
pipeline {
   agent none
   stages {     
    stage('Maven Install') {
      agent {         
       docker {          
         image 'maven:3.5.0'         
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
