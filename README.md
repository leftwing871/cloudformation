# cloudformation


## Create Stack
  ```
  aws cloudformation create-stack --stack-name ProductA --template-body file://Network.yml
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
