pipeline{
 tools{
        jdk 'JAVA_HOME'
        maven 'M2_HOME'
    }
     agent any
	  
	  stages{
	  
	  stage("checkout"){
	   steps{
	   git 'https://github.com/ashisnishanka/gitrealtime.git'
	   }
	                  }
	
	   stage("compile"){
	    steps{
		 sh 'mvn compile'
		}
		stage("testcase")
		{
		  steps
		  {
		  
		   sh 'test'
		  }
		}
		}
	  }
	}
