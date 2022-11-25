pipeline {
  agent any
    
  tools {nodejs "nodejs"}
    
  stages {
        
    stage('Git') {
      steps {
        git branch: 'main', url: 'https://github.com/sgeethapriya/nodejs_sample.git'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
         sh 'node hello_world.js'
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
