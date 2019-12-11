pipeline
{
    agent none
    stages
    {
        stage('Fetch')
        {
            echo "git fetch origin"
        }
        stage('Compile')
        {
            bat 'mvn -B -DskipTests clean package'
        }
        stage('Test')
        {
            bat 'mvn test'
        }
    }
}





