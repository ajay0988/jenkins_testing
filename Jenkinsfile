pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "mavenslave"
            }
          
          steps {
             
                echo "my master branch"
                sh "mvn -version"
          }
        }
   }
}
