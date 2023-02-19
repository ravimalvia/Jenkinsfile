pipeline {
	agent {
		label "slave"
	}
	stages {
		stage("git"){
 			steps {
				git 'https://github.com/ravimalvia/helloworld.git'
			}

		}
		stage("second"){
			steps {
				echo "HII iam second step"
			}
		
		}

	}
}

