pipeline{
    agent any 
    stages{
        stage("Build app"){
            steps{
                 dir("/e9-cloudformation-docker-ecs/infra") {
                 sh "aws cloudformation create-stack --stack-name app --template-body file://api.yml"
                 }
            }
        }
    }
}
