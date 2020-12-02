pipeline {
    agent any
        stages {    
            stage ("first") {    
                steps {       
                sh "pwd"   
                }
            }            
	       stage ("two") {    
                steps {       
                sh "docker ps -a"    
                }
            }	            
            stage ("three") {    
                steps {       
            	sh "whoami"
		}
            }            
        }      
}
