pipeline {
	agent any
	stages {
		stage('Build master') {
			when {
				changelog '.*some_text.*'
			}
		}

	}
}
