pipeline{

	agent any
	
	stages{
		stage('build'){
			steps{
				echo 'build...'
			}
		}

		stage ('deploy'){
			steps{
				echo 'deploy...'
			}
		}
		
		stage ('example'){
			steps{
				echo "Running ${env.BUILD_ID} on ${JENKINS_URL}"
			}
		}
	}
}
