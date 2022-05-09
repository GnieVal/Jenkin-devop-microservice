//Declarative Syntax
pipeline {
	agent any 
	  stages {
        stage ('Build') {
		   steps {
			   echo "Build"

		   }	
		}

		stage ("Test") {
			steps {
			   echo "Test"
			}
		}

		stage ('Integrated Test') {
			steps{
				echo "Integration Test"
			}
		}

	}
		
	post {
        always {
			echo 'I am awesome. I run always'
		}
        success {
			echo 'I run when I am successful'
		}

		failure {
			echo 'I run when i fail'
		}

	}
	
}
