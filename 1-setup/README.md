# Setting up the Project and the Development Environment

## Create serverless project

``` nodejs
sls create --template aws-nodejs -p verify
```

## Deploy serverless function

``` nodejs
sls deploy --aws-profile manning
```

## Invoke serverless function

``` nodejs
sls invoke -f hello --aws-profile manning
```

## Output

``` json
{
    "statusCode": 200,
    "body": "{\n  \"message\": \"Go Serverless v1.0! Your function executed successfully!\",\n  \"input\": {}\n}"
}
```
