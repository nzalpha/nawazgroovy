pipeline{
    agent any
    environment deploy_to = 'prod'
    stages{
        stage('Build')
        {
            when{
                environment name: 'deploy_to', value: 'other'
            }
            steps{
                echo "Build Prod pipeline"
            }
        }
    
    }
}
