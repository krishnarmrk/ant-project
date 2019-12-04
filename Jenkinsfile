pipeline {
	agent any
	stages {
		stage ('Checkout') {
		    steps {
		        echo "Checkout the code"
		    }
		}
		
		stage ('Build') {
            		steps {
               		echo "Building the code"
			    }
			}
	
		stage ('Test') {
        	    steps {
		        echo "Testing the code"
			    }
			}
		
		stage ('QA') {
	            steps {
		        echo "QA Analysing the code"
			    }
			}
	
		stage ('Deploy') {
	            steps {
		        echo "Deploying the code"
			    }
			}
	
		stage ('Moniter') {
	            steps {
		        echo "Application Support team monitioring the code"
			    }
			}
		}
}
