pipeline{
    agent any 
    stages{
        stage("Build app"){
            steps{
                 sh "aws cloudformation create-stack --stack-name app --template-body file://root.yaml --region 'ap-south-1'"
                 }
        }
    }
}
