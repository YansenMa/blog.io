# CDK

The `AWS Cloud Development Kit (AWS CDK)` is an open source software development framework to model and provision your cloud application resources using familiar programming languages.


A `Stack` is the unit of deployment within the CDK, every stack has an `Environment` that specifies account and region.


```bash 

## check version
cdk version

## create/init cdk project
cdk init TEMPLATE --language LANGUAGE


## boostrap the AWS env
cdk bootstrap

## List the stacks in the CDK app
cdk list

## Deloy CDK stack
cdk deploy

## Delete the stack
cdk destroy

## Launch the CDK Doc
cdk docs

## Compare local and deployed stack
cdk diff 

## Generates CloudFormation templates
cdk synth

```
