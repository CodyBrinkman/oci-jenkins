pipeline {

	agent any
	
	stages {
		
		stage('First stage to make sure Jenkinsfile working') {

			steps {

				echo 'This is working!'				

			}

		}

		stage('Testing OCI connection') {

			steps {


				echo 'Testing connection to OCI'
				script {


						sh "whoami"
						sh "oci"

					}	

			}				

		}
	
	}

}
