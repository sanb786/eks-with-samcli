# sb-test-cf

## Deploy the sample application

The Serverless Application Model Command Line Interface (SAM CLI) is an extension of the AWS CLI that adds functionality for building and testing Lambda applications. It uses Docker to run your functions in an Amazon Linux environment that matches Lambda. It can also emulate your application's build environment and API.

To use the SAM CLI, you need the following tools.
```bash
sam build
sam deploy --guided
```

Build your application with the `sam build` command.

```bash
sb-test-cf$ sam build
```

https://docs.aws.amazon.com/eks/latest/userguide/creating-a-vpc.html