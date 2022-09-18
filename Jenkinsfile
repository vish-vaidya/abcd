pipeline {
agent {

node {
			label 'master'
			customWorkspace '/mnt/project/game-of-life'

}

}

stages {

	stage ('clean'){
	
		steps {
				sh "mvn clean"
		}
	
	}

	stage ('installing'){
	
		steps {
				sh "mvn install"
                       
		}
	
	}
}
}
