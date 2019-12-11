pipeline
{
    agent none
    stages
    {
        stage('Fetch')
        {
            steps
            {
                    echo "git fetch origin"
            }
        }
        stage('Compile')
        {
        docker.image('node:7-alpine').inside
            {
                steps {
                    bat 'mvn -B -DskipTests clean package'
                    }
            }
        }
            stage('Test')
            {
         docker.image('node:7-alpine').inside
                {
                  steps {
                    bat 'mvn test'
                        }
                }
            }
    }
}





