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
       
     
    
