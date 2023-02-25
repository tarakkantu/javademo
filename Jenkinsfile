pipeline {
  agent any 
  stages {
    stage("stage1") {
	  steps {
	    bat "echo hello tarachandra"

	  }
	}
	stage("stage2") {
	  steps {
	    bat "echo stage2"
		bat "mvn clean install"
	  }
	}
  }
}
