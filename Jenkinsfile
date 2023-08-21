pipeline {
	agent {docker {image 'maven:3.6.3'}}
	stages{
		stage('Build') {
			steps
			{
				sh 'mv --version'
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
