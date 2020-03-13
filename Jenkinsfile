pipeline {
	agent any
	stages {
		stage('Build master') {
			when {
				changeRequest title: "when-pr"
			}
			steps {
				echo "Hellow World !!! Changing request"	
			}
		}
		

	}
}
