pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean -f "D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins\\pom.xml"'
            }
        }
	stage('Test') {
	steps {
                bat 'mvn test -f "D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins\\pom.xml"'
		}
}

    }
}