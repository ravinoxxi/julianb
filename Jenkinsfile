pipeline{
	agent any
	stages{
		stage('Starting'){
			steps{					
				sh 'sudo docker ps'
				sh 'echo starting.....'

					}
				}

	stage('Build Image PHP54'){
			steps{					
				sh 'sudo docker build --tag=php54 .'

					}
				}

	}
}
