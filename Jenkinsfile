pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "mavenslave"
            }
          
          steps {
             
                echo "my dev branch"
                sh "mvn -version"
          }
        }
   }
}
