pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat "D:"
                bat "cd D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins"
                bat 'mvn compile'
            }
        }
	stage('Test') {
	steps {
	    bat "D:"
        bat "cd D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins"
		bat 'mvn test'
		}
}

    }
}