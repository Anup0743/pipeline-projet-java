pipeline
{
    agent any
    stages
    {
        stage('compile')
        {
            steps
            {
                echo "complieing the code"
                bat 'javac Test.java'

            }
        }
        stage('build')
        {
            steps
            {
                echo "build the code"
                bat 'java Test' 

            }
        }
        stage('deploy')
        {
            steps
            {
                echo "deploy the code"
               

            }
        }
    }
}