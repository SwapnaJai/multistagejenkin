pipeline{
  agent any 
   stages{
     stage('First:Git Code'){
       steps{
               git'https://github.com/SwapnaJai/multistagejenkin.git'
          }
     }
       stage('Build'){
          steps{
                 sh 'echo "Building the application..."'
             }
     } 
        stage('Test'){
          steps{
                  sh 'echo "Running tests..."'
          }
     }
   }
}            
       
     
    
