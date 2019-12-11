pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                call '/user:administrator mvn clean'
                call '/user:administrator mvn compile'
            }
        }
	stage('Test') {
	steps {
		call '/user:administrator mvn test'
		}
}

    }
}