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
       sh "ciao"
       sh 'mvn clean install'
       echo "prova"
       }
     }
   }
 }
