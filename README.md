# cloudformation


## Create Stack
  ```
  aws cloudformation create-stack --stack-name ProductA --template-body file://Network.yml
  aws cloudformation create-stack --stack-name ProductB --template-body file://Network03.yaml --parameters ParameterKey=KeyName,ParameterValue=YOUR_KEY
  aws cloudformation create-stack --stack-name String --template-body file://string.yaml --capabilities "CAPABILITY_IAM"
aws cloudformation create-stack --stack-name StringExample --template-body file://string_example.yaml  --parameters ParameterKey=InputString,ParameterValue=DevOpsEng --capabilities "CAPABILITY_AUTO_EXPAND"
  ```
### Wait 
  ```
  aws cloudformation wait stack-create-complete --stack-name [INPUT_CREATED_ARN]
  ```

## Update Stack
  ```
  aws cloudformation update-stack --stack-name ProductA --template-body file://Network.yml
  ```

## Delete Stack
  ```
  aws cloudformation delete-stack --stack-name ProductA
  ```

# Ref
  ```
  아래 링크를 참조하세요
  ```  
  - [aws-vpc-cloudformation](https://www.infoq.com/articles/aws-vpc-cloudformation/)
  - [Sample Solutions](https://docs.aws.amazon.com/ko_kr/AWSCloudFormation/latest/UserGuide/sample-templates-applications-ap-northeast-2.html)
  - [Application frameworks](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/sample-templates-appframeworks-ap-northeast-2.html)
  - [Sample template Services](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/sample-templates-services-ap-northeast-2.html#w2ab1c33c32c13b7)
  - [Macro Examples](https://github.com/awslabs/aws-cloudformation-templates/tree/master/aws/services/CloudFormation/MacrosExamples)
  - [AWS Quick Starts](https://aws.amazon.com/ko/solutions/)

