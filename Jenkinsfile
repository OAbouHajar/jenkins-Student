pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat "D:"
                bat "cd D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins"
                call 'mvn clean'
                call 'mvn compile'
            }
        }
	stage('Test') {
	steps {
	    bat "D:"
        bat "cd D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins"
		call 'call mvn test'
		}
}

    }
}