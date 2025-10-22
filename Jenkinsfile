pipeline{
  agent any 
   stages{
     stage('first:SCM GIT'){
       steps{
             git'https://github.com/SwapnaJai/multistagejenkin.git'
          }
     }
       stage('Second:build'){
          steps{
                sh 'echo "building the app"'
              }
     } 
        stage('Third:Test'){
          steps{
                 sh 'echo "test the app"'
          }
     }
   }
}            
       
     
    
