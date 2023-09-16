pipeline{
 tools{
      maven 'maven-install'
    }
     agent any
	  
	  stages{
	  
	  stage("checkout1"){
	   steps{
	   git 'https://github.com/ashisnishanka/gitrealtime.git'
	   }
	                  }
	
	   stage("compile"){
	    steps{
		 sh 'mvn compile'
		}
	   }
		stage("testcase")
		{
		  steps
		  {
		   sh 'mvn test'
		  }
		}
	  }
	}
