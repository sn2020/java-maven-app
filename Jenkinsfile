pipeline {
  
  agent none {
    
    stages {
      
      stage ("build") {
        step {
          script {
          echo "Building from Jenkinsfile"
          }  
        }
      }  
      stage ("Test") {
        step {
          script {
            echo "Testing from Jenkinsfile"
          }  
        }
      }
      stage ("Deploy") {
        step {
          script {
            echo "Deploying from Jenkinsfile"
          }          
         }
      }
    }
  }
}
