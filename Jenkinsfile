pipeline{
    agent any 
    stages{
        stage("Build app"){
            steps{
                 sh "aws cloudformation update-stack --stack-name app --template-body file://root.yaml  --capabilities CAPABILITY_IAM --region 'ap-south-1'"
                 }
        }
    }
}
