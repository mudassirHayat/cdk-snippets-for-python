# CDK Snippets for Python

A minimal set of code snippets for AWS CDK v2 to boost your productivity.


![CDK Snippets for Python Tutorial](./docs/images/tutorial.gif)

## Catalog

Following are the snippets available at this moment:

### api-gateway

| Prefix | Description |
|--------|-------------|
| apigw-add-method | Generate an API Gateway method |
| apigw-add-model | Generate an API Gateway model |
| apigw-add-proxy | Generate an API Gateway proxy |
| apigw-add-resource | Generate an API Gateway resource |
| apigw-asset-api-definition | Generate an API Gateway Asset API definition |
| apigw-aws-integration | Generate an API Gateway AWS integration |
| apigw-http-integration | Generate an API Gateway HTTP integration |
| apigw-inline-api-definition | Generate an API Gateway Inline API definition |
| apigw-lambda-integration | Generate an API Gateway lambda integration |
| apigw-lambda-rest-api | Generate an API Gateway Lambda REST API |
| apigw-request-authorizer | Generate an API Gateway request authorizer |
| apigw-rest-api | Generate an API Gateway REST API |
| apigw-s3-api-definition | Generate an API Gateway S3 API definition |
| apigw-spec-rest-api | Generate an API Gateway Spec REST API |
| apigw-token-authorizer | Generate an API Gateway token authorizer |

---

### dynamodb

| Prefix | Description |
|--------|-------------|
| ddb-attribute | Add a DynamoDB table attribute |
| ddb-gsi | Generate a DynamoDB global secondary index |
| ddb-lsi | Generate a DynamoDB local secondary index |
| ddb-table | Generate a DynamoDB table |

---

### events-targets

| Prefix | Description |
|--------|-------------|
| events-targets-api | Generate an Event Bridge AWS API target |
| events-targets-batch-job | Generate an Event Bridge AWS Batch job target |
| events-targets-code-build-project | Generate an Event Bridge CodeBuild project target |
| events-targets-code-pipeline | Generate an Event Bridge CodePipeline target |
| events-targets-ecs-task | Generate an Event Bridge ECS task target |
| events-targets-kinesis-firehose-stream | Generate an Event Bridge Kinesis Firehose stream target |
| events-targets-kinesis-stream | Generate an Event Bridge Kinesis stream target |
| events-targets-lambda-function | Generate an Event Bridge Lambda function target |
| events-targets-sfn-state-machine | Generate an Event Bridge Step Function state machine target |
| events-targets-sns-topic | Generate an Event Bridge SNS topic target |
| events-targets-sqs-queue | Generate an Event Bridge SQS queue target |

---

### events

| Prefix | Description |
|--------|-------------|
| events-rule | Generate an Event Bridge rule |
| events-schedule-cron | Generate an Event Bridge schedule crontab statement |
| events-schedule-expression | Generate an Event Bridge schedule expression statement |
| events-schedule-rate | Generate an Event Bridge schedule rate statement |

---

### iam

| Prefix | Description |
|--------|-------------|
| iam-account-principal | Generate an IAM account principal |
| iam-arn-principal | Generate an IAM ARN principal |
| iam-aws-managed-policy-by-name | Import an AWS managed policy by name |
| iam-import-role | Import an IAM role by ARN |
| iam-managed-policy-by-arn | Import a customer managed policy by ARN |
| iam-managed-policy-by-name | Import a customer managed policy by name |
| iam-organization-principal | Generate an IAM organization principal |
| iam-policy-document | Generate an IAM policy document |
| iam-policy-statement | Generate an IAM policy statement |
| iam-role | Generate an IAM role |
| iam-service-principal | Generate an IAM service principal |

---

### kms

| Prefix | Description |
|--------|-------------|
| kms-key | Generate a KMS key |
| kms-key-from-alias | import a KMS key by alias |
| kms-key-from-arn | Import a KMS key by ARN |

---

### lambda

| Prefix | Description |
|--------|-------------|
| lambda-code-from-asset | Import Lambda function code from local assets |
| lambda-code-from-bucket | Import Lambda function code from S3 |
| lambda-code-from-inline | Import Lambda function code from inline |
| lambda-function | Generate a Lambda function |

---

### s3

| Prefix | Description |
|--------|-------------|
| s3-block-config | Generate S3 block public access configuration |
| s3-bucket | Generate S3 bucket |
| s3-import-from-arn | Import S3 bucket by ARN |
| s3-import-from-attributes | Import S3 bucket by attributes |
| s3-import-from-name | Import S3 bucket by name |

---

### sns-subscription

| Prefix | Description |
|--------|-------------|
| sns-subscription-email | Add an email subscription |
| sns-subscription-lambda | Add a Lambda subscription |
| sns-subscription-sms | Add a SMS subscription |
| sns-subscription-sqs | Add a SQS subscription |
| sns-subscription-url | Add a SNS subscription |

---

### sns

| Prefix | Description |
|--------|-------------|
| sns-topic | Add a SNS topic |
| sns-topic-from-arn | Import a SNS topic by ARN |

---

### step-functions-tasks

| Prefix | Description |
|--------|-------------|
| step-function-task-batch | Add a Step Function Task for AWS Batch submit job |
| step-function-task-code-build | Add a Step Function Task for CodeBuild start build |
| step-function-task-dynamo-attribute-value | Generate a DynamoDB attribute value statement for Step Function Task |
| step-function-task-dynamo-delete-item | Add a Step Function Task for DynamoDB delete item |
| step-function-task-dynamo-get-item | Add a Step Function Task for DynamoDB get item |
| step-function-task-dynamo-put-item | Add a Step Function Task for DynamoDB put item |
| step-function-task-dynamo-update-item | Add a Step Function Task for DynamoDB update item |
| step-function-task-evaluate | Add a Step Function Task Evaluate |
| step-function-task-invoke-activity | Add a Step Function Task for Step Function invoke activity |
| step-function-task-lambda-invoke | Add a Step Function Task for Lambda invoke |
| step-function-task-sns-publish | Add a Step Function Task for SNS publish |
| step-function-task-sqs-send-message | Add a Step Function Task for SQS send message |
| step-function-task-start-execution | Add a Step Function Task for Step Function start execution |

---

### step-functions

| Prefix | Description |
|--------|-------------|
| step-function-activity | Generate a Step Function Activity |
| step-function-choice | Generate a Step Function Choice state |
| step-function-condition | Generate a Step Function Condition statement |
| step-function-custom-state | Generate a Step Function CustomState state |
| step-function-fail | Generate a Step Function Fail state |
| step-function-integration-pattern | Add a Step Function Integration Pattern value |
| step-function-json-path | Add a Step Function Json Path statement |
| step-function-map | Generate a Step Function Map state |
| step-function-parallel | Generate a Step Function Parallel state |
| step-function-pass | Generate a Step Function Pass state |
| step-function-state-machine | Generate a Step Function state machine |
| step-function-succeed | Generate a Step Function Succeed state |
| step-function-task-input | Add a Step Function Task Input statement |
| step-function-wait | Generate a Step Function Wait state |
| step-function-wait-time | Generate a Step Function WaitTime statement |

---

## Feature Request

If you have a feature request or an issue, please head over to issues on [GitHub](https://github.com/sameeramin/cdk-snippets-for-python/issues).

## Release Notes

### 1.0.0

Initial release of CDK Snippets for Python.


## Contributing
You're welcome to contribute to this project by adding more snippets or fixing existing ones.

## Authors
[Muhammad Sameer](https://github.com/sameeramin), [Ayesha Goheer](https://github.com/ayeshaq2022skipq)