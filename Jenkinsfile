pipeline {
agent {

node {
			label 'master'
			customWorkspace '/mnt/project'

}

}

stages {

	stage ('compile'){
	
		steps {
				sh "mvn compile"
		}
	
	}

	stage ('installing'){
	
		steps {
				sh "mvn install"
                       
		}
	
	}
}
}
