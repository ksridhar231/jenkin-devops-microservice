pipeline {
	agent any
	stages{
		stage('Build') {
			steps
			{
				echo "Build"
			}
		
		}
		stage('Test') {
			steps
			{
				echo "Test"
			}
		
		}

		stage('Deploy') {
			steps
			{
				echo "Deploy"
			}
		}
	}
	post{
		always{
			echo "I always do this"
		}
		success{
			echo "I always do when am success"
		}
		failure{
			echo "I always do this when fail"
		}
	}
	
}
