## Examples of various Lambda function integrations with API Gateway and CORS enabled

Why? When working with Lambda functions, there are various different things to take into consideration.

- Is this function being invoked from an HTTP trigger?
- Is this function using API Gateway?
- Are you calling this function from a client-side application?
- Are you running into CORS issues when fetching data from your Lambda function?

If you answered yes to these questions, then these copy-paste examples should help you to get up and running with many of the most popular runtimes.

Here are the supported runtimes that I will be creating examples for:

### Go

[main.go](https://github.com/dabit3/api-gateway-lambda-in-various-runtimes/blob/master/main.go)

### Python

[index.py](https://github.com/dabit3/api-gateway-lambda-in-various-runtimes/blob/master/index.py)

### .Net

[handler.cs](https://github.com/dabit3/api-gateway-lambda-in-various-runtimes/blob/master/handler.cs)

### NodeJS / JavaScript

[index.js](https://github.com/dabit3/api-gateway-lambda-in-various-runtimes/blob/master/index.js)

### Java

[handler.java](https://github.com/dabit3/api-gateway-lambda-in-various-runtimes/blob/master/handler.java)

Check out [this serverless example](https://github.com/serverless/examples/tree/master/aws-java-simple-http-endpoint) for a full Java implementation

## More examples

For more examples of Lambda integrations in different languages, check out the [Serverless Examples](https://github.com/serverless/examples)