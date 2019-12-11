pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                call 'mvn clean'
                call 'mvn compile'
            }
        }
	stage('Test') {
	steps {
		call 'call mvn test'
		}
}

    }
}