pipeline{
    agent any
    stages{
        stage('QRBuild')
        {
            steps{
                echo "QRBuild pipeline"
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
