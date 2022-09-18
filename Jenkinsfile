pipeline {
agent {

node {
			label 'master'
			customWorkspace '/mnt/newproject'

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
