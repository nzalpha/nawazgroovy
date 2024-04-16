pipeline{
    agent any
    stages{
        stage('TestingBuild')
        {
            steps{
                echo "Testing Build pipeline"
            }
        }

         stage('Scans')
        {
            steps{
                echo "Scanning pipeline"
            }
        }

         stage('Docker Build')
        {
            steps{
                echo "Docker build pipeline"
            }
        }
         stage('Dev Deploy')
        {
            steps{
                echo "Deploying Dev "
            }
        }
    }
}
