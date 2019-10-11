# Example AWS Lambda C# .NET Core 2.2 with connect MySQL via Linq2db

## Test and Deploy with AWS CLI

**Deploy**
```
$ cd src/aws-lambda-db
$ dotnet lambda deploy-function {LAMBDA_FUNCTION_NAME} –-function-role {ROLE_NAME}
```

**Try to Run and Get result**
```
$ cd src/aws-lambda-db
$ aws lambda invoke --function-name {LAMBDA_FUNCTION_NAME} output.txt
```