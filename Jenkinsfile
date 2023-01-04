pipeline { 
  
   agent any

   stages {
   
     stage('FirstStage') { 
        steps { 
           sh 'echo "firststage"' 
        }
     }
     
     stage('2ndTest') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("3rdDeploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
