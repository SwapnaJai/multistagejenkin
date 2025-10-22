pipeline{
  agent any 
   stages{
     stage('first stage'){
       steps{
             git'https://github.com/SwapnaJai/multistagejenkin.git'
          }
     }
       stage('build'){
          steps{
                sh 'echo "building the app"'
              }
     } 
        stage('Test'){
          steps{
                 sh 'echo "test the app"'
          }
     }
   }
}            
       
     
    
