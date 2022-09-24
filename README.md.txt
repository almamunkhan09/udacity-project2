This yml file create a cloudformation stack that creats the infrastructure like the picture.
S3 is only accessible from EC2



The command for creating the stack is 
aws cloudformation create-stack --stack-name project2 --template-body file://awscf.yaml    --parameters file://parameters.json  --region=us-east-1 --capabilities CAPABILITY_NAMED_IAM

Then in EC2 Load Balancer section you will get a link like this 

infra-WebAp-11ZAFYSYJML8D-822091127.us-east-1.elb.amazonaws.com