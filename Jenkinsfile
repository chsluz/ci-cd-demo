pipeline {

	agent any
	
	stages {
	
		stage("build") {
		
			steps {
				sh 'mvn clean install'
			}
			
		}
		
		stage("test") {
		
			steps {
			 echo 'testing the application ....'
			}
		}
		
		stage("deploy") {
			
			steps {
			 echo 'deploy the application ....'
			}
		}
	}
}