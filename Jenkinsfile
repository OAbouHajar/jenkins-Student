pipeline {
    agent any
    stages {
    stage('Fetch') {
                steps {
                    echo "fetch data from orgin"
                }
            }
        stage('Build') {
            steps {
                bat 'mvn clean -f "D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins\\pom.xml"'
            }
        }
	stage('Test') {
	steps {
                bat 'mvn package -f "D:\\IT Carlow\\Year4\\Soft Eng\\jenkins\\Student-jenkins\\pom.xml"'
		}
}

    }
}