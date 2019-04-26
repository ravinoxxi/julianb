pipeline{
	environment{
		registry = "ravinoxxi/julianb"
		registryCredential = "dockerhub"
	}
	agent any
	stages{
		stage('Starting'){
			steps{					
				sh 'sudo docker ps'
				sh 'echo starting.....'

					}
				}

	stage('Build Container'){
			steps{					
				script{
					dockerImage=docker.build registry + ":$BUILD_NUMBER"

					}
				}	
		
			}
		}
	}
