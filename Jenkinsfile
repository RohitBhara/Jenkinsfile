pipeline {
   label {
       label "built-in"
	   customWorkspace = "/mnt/jenkins"
   
   
   }
      envoirment {
	       var1 = " HII IAM ROHIT"
	    
	  }
   
       stages {
	      stage("parallel") {
		    parallel {
			  stage ("fisrt") {
			     steps {
			         sleep 10 
			  }
			  
			  }
			  stage ("2nd") {
			    steps {
				  echo "${var1}"
				
				}
			  }
			
			
			}
		  
		  
		  }
	   
	   }
} 
