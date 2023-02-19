@Library('Shared-library') _
pipeline {
    agent { label "slave" }
    stages {
        stage('Hello') {
            steps {
                helloWorld()
            }
        }
    }
}
