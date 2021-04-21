pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "mavenslave"
            }
          
          steps {
             
                sh '''
                    echo "MASTER branch"
                    pwd
                '''
          }
        }
   }
}
