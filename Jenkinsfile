pipeline {
	agent any
	stages {
		stage('Build master') {
			when {
				branch 'master'
			}
			steps {
				echo "Building master now ..."
			}
		}
		stage('Build jenkins') {
			when {
				branch 'jenkins'
			}
			steps {
				echo "Building jenkins now ..."
			}
		}
	}
}
