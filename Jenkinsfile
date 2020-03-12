pipeline {
	agent any
	stages {
		stage('Build master') {
			when {
				changeRequest()
			}
			steps {
				echo "Hellow World !!! Changing request"	
			}
		}
		

	}
}
