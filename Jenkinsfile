#!/usr/bin/env groovy
 
node {
    
   stage('setup') { 
   
      // Get some code from a GitHub repository
    try{

	sh 'cd ~/'
        git 'https://github.com/mainul35/jenkins-pipeline-practice.git'
 
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
