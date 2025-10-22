pipeline{
  agent any 
   stages{
     stage('First:Git Code'){
       steps{
             git'https://github.com/SwapnaJai/multistagejenkin.git'
          }
     }
       stage('Second:build'){
          steps{
               bat 'echo "building the app"'
              }
     } 
        stage('Third:Test'){
          steps{
                 bat 'echo "test the app"'
          }
     }
   }
}            
       
     
    
