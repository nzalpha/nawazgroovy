pipeline{
    agent any
    stages{
        stage('Build')
        {
            steps{
                echo "Build pipeline"
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
