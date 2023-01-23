# AWS SAM Python Devcontainer

Develop AWS SAM with devcontainer.

## Getting started

https://docs.aws.amazon.com/ja_jp/serverless-application-model/latest/developerguide/serverless-getting-started-hello-world.html

### Build
```bash
$ cd sam-app/
$ sam build --profile YOUR_AWS_PROFILE
```

### Local Testing

```bash
$ cd sam-app/
$ sam local start-api --host 0.0.0.0 --container-host host.docker.internal --profile YOUR_AWS_PROFILE 
```

TODO:not working

### Deploy
```bash
$ cd sam-app/
$ sam deploy --guided --profile YOUR_AWS_PROFILE
or
$ sam deploy --stack-name sam-app --profile YOUR_AWS_PROFILE
```

### Delete
```bash
$ cd sam-app/
$ sam delete --stack-name sam-app --profile YOUR_AWS_PROFILE
```
