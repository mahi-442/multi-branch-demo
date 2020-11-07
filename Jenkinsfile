pipeline{
    agent any
    stages{
        stage('Deploy Dev'){
            when{
                branch 'devlopment'
            }
            steps{
                echo "Deploying to Dev environment"
            }
        }
        stage('Deploy Staging'){
            when{
                branch 'staging'
            }
            steps{
                echo "Deploying to Staging environment"
            }
        }
        stage('Deploy Prod'){
            when{
                branch 'master'
            }
            steps{
                echo "Deploying to prod environment"
            }
        }
    }
}