pipeline {
	agent any
	stages {
		stage('Build') {				
			steps {				
				sh '''		
					sleep 1
					echo "this is a Build stage"
				   '''
			}
		}
		stage('Deploy') {
			steps {
				sh 'sleep 1; echo "this is a Deploy stage"'		
			}
		}
		stage('Test') {
			steps {
				sh 'sleep 1; echo "this is a Test stage"'
			}
		}
	}
}
