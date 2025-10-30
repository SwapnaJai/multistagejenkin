pipeline{
  agent any 
   stages{
     stage('First:Git Code'){
       steps{
             git'https://github.com/SwapnaJai/multistagejenkin.git'
          }
     }
       stage('Second:Build'){
          steps{
               'echo building the app'
             }
     } 
        stage('Third:Test'){
          steps{
               'echo test the app'
          }
     }
   }
}            
       
     
    
