pipeline {
    agent none
    stages {
        stage('Fetch') {
            steps {
                    echo "git fetch origin"
            }
        }
        stage('Compile') {
            steps {
                bat 'mvn -B -DskipTests clean package'
	            }
        }
            stage('Test') {
              steps {
                bat 'mvn test'
              }
            }

    }
}





