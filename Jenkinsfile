pipeline{
	agent any
	stages{
		stage("Run Test"){
			steps{
				bat "docker-compose up -d"
			}
		}
		stage("Bring Grid Down"){
			steps{
				bat "docker-compose down"
			}
		}
	}
}