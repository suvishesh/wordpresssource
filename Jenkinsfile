pipeline {
    agent any
        stages {    
            stage ("first") {    
                steps {       
                pwd   
                }
            }            
	       stage ("two") {    
                steps {       
                docker ps -a    
                }
            }	            
            stage ("three") {    
                steps {       
            	whoami
		}
            }            
        }      
}
