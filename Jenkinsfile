#!/usr/bin/env groovy

node {
   stage('setup') { 
   
      // Get some code from a GitHub repository
      try{
         sh 'ssh root@192.168.1.33'
         sh 'ifconfig'
         sh 'cd ~/'
         sh 'git clone https://github.com/mainul35/jenkins-pipeline-practice.git'
      }
      catch (err){
         echo err
      }
    
   }
   stage('build') {
      // Installing Dependencies
     // sh 'npm install'
   }
   
   stage('test') {
         
   }
   stage('end') {  
     echo "Success" 
   }
}
