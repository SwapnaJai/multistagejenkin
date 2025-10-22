pipeline{
  agent any 
   stages{
     stage('first stage'){
       steps{
         git''
       }
       stage(second :build'){
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
              
       
     
    
