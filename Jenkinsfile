pipeline{
    agent any
    stages{
        stage(Deploy dev){
            when{
                branch 'devlopment'
            }
            steps{
                echo "Deploying to Dev environment"
            }
        }
        stage(Deploy staging){
            when{
                branch 'staging'
            }
            steps{
                echo "Deploying to Staging environment"
            }
        }
        stage(Deploy prod){
            when{
                branch 'master'
            }
            steps{
                echo "Deploying to prod environment"
            }
        }
    }
}