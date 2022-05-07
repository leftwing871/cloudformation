# cloudformation


## Create Stack
  ```
  aws cloudformation create-stack --stack-name ProductA --template-body file://Network.yml
  aws cloudformation create-stack --stack-name ProductB --template-body file://Network03.yaml --parameters ParameterKey=KeyName,ParameterValue=YOUR_KEY
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
  https://www.infoq.com/articles/aws-vpc-cloudformation/
  ```  

  - [Sample Solutions](https://docs.aws.amazon.com/ko_kr/AWSCloudFormation/latest/UserGuide/sample-templates-applications-ap-northeast-2.html)
  - [Application frameworks](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/sample-templates-appframeworks-ap-northeast-2.html)
  - [Sample template Services](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/sample-templates-services-ap-northeast-2.html#w2ab1c33c32c13b7)
  - [Macro Examples](https://github.com/awslabs/aws-cloudformation-templates/tree/master/aws/services/CloudFormation/MacrosExamples)

