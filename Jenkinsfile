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
                sh "ls -a"    
                }
            }	            
            stage ("three") {    
                steps {       
            	sh "whoami"
		}
            }            
        }      
}
