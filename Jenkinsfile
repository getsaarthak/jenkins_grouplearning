pipeline {
	agent any
	stages {
		stage('Build master') {
			when {
				changelog '.*some_text.*'
			}
			steps {
				echo "Building the change log"	
			}
		}
		

	}
}
