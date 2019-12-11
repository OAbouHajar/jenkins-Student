pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                call "D:"
                call "cd D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins"
                call 'mvn clean'
                call 'mvn compile'
            }
        }
	stage('Test') {
	steps {
	    call "D:"
        call "cd D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins"
		call 'mvn test'
		}
}

    }
}