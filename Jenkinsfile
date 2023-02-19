pipeline {
	agent {
		label "slave"
	}
	stages {
		stage("Git downlaod step"){
 			steps {
				git 'https://github.com/ravimalvia/helloworld.git'
			}

		}
		stage("Build Step"){
			steps {
				sh 'mvn clean package'
			}
		
		}

	}
}

