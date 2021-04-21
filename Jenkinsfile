pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "mavenslave"
            }
          
          steps {
             
                echo "my dev branch",
              sh '''#!/bin/bash

                    echo "Hello from bash"
                    echo "Who I'm $SHELL"
                    mvn -version
                    java -version
                '''
          }
        }
   }
}
