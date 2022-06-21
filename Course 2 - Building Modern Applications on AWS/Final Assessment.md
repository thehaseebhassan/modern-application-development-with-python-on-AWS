# Building Modern Python Applications on AWS - Coursera

## End of Course Assessment

### Question 1

Lambda@Edge is a feature of Amazon CloudFront that lets code run closer to the users of distributed applications, helping to improve performance and reduce latency.

- [x] True

- [ ] False


### Question 2

In which scenario would Cognito User Pool be the right choice to use over a Cognito Identity Pool?

- [x] The application behind API Gateway (backend) needs to have information about the user.

- [ ] API Gateway, Simple Storage Service, DynamoDB and other AWS services will be used directly by the application.

- [ ] My application requires unauthenticated users to access parts of my application.

- [ ] The authorizer of the API method is set to AWS_IAM in API Gateway.


### Question 3

In which of the following locations is Amazon CloudFront hosted?

- [ ] Local zone

- [ ] Availability zone

- [ ] Region

- [x] Edge location


### Question 4

When the application code in a Lambda function needs to communicate with a relational database, which feature of the AWS Lambda service would minimize the amount of connections to that relational database?

- [ ] Synchronous invocation

- [ ] Provisioned Concurrency

- [ ] Automatic scaling

- [x] Execution context reuse


### Question 5

What is the maximum timeout or maximum amount of time for the execution of a Lambda function?

- [ ] 5 hours
 
- [ ] 15 hours

- [x] 15 minutes

- [ ] 5 minutes


### Question 6

What feature can be used to know if a Lambda function, that was asynchronously invoked, executed successfully? 

- [ ] Looking at the response code

- [ ] Retries

- [x] Destinations

- [ ] Dead-letter queue


### Question 7

What actions within AWS are done as an API call?

- [ ] About half of the actions

- [ ] Some actions

- [x] Almost all of the actions

- [ ] A few actions


### Question 8

When AWS Lambda executes your Lambda function, it provisions and manages the resources needed to run your Lambda function. This is called the execution context, and it is a temporary runtime environment. After a Lambda function is executed, AWS Lambda maintains the execution context for some time in anticipation of another Lambda function invocation. 

What can you do in your code to take advantage of execution context re-use for performance optimization? Select two.

- [x] Declare objects outside of the handler method 

- [ ] Store data in environment variables as a cache

- [x] Write data to the /tmp directory to be used as a transient cache

- [ ] Write code that pings your lambda function once an hour to keep the execution context alive


### Question 9

What types of APIs can Amazon API Gateway NOT be used to create?

- [ ] HTTP

- [ ] WebSocket

- [x] BPM

- [ ] REST


### Question 10

In which of the following use case a Lambda layer should NOT be used?

- [ ] I would like to share my custom runtime with others.

- [ ] I would like to keep my Lambda deployment package small.

- [x] I would like to separate all my small libraries individually to share across Lambda functions.

- [ ] I would like to share code across many different Lambda functions in different AWS accounts.


### Question 11

Which of the following statement is true when using AWS Lambda layers?

- [ ] Layers are shared automatically with every AWS customer.

- [ ] Lambda functions can only use Lambda layers created in the same AWS account.

- [x] The maximum size of the Lambda deployment package including layers is 250 MB.

- [ ] A Lambda function can only use one layer at a time.


### Question 12
What is the easiest way to send logs to Amazon CloudWatch Logs from code in a Lambda function?

- [x] Write to stdout or stderr and logs will be sent automatically

- [ ] Make an HTTPS call to Amazon CloudWatch logs

- [ ] Use the Amazon CloudWatch SDK to send logs

- [ ] Use the syslog library to send logs directly to CloudWatch logs


### Question 13
A state machine in AWS Step Function is used for doing continuous deployment as part of a pipeline. One of the steps is to use Lambda to send an email asking for a manager to approve or not the deployment in production. Which of the following service integration pattern should be used?

- [ ] Request Response

- [x] Wait for Callback

- [ ] Activity task

- [ ] Run a Job


### Question 14

When using the AWS SDK for X-Ray, to measure granular performance of a singular API call or specific line(s) of code, you can create a new:

- [ ] Trace

- [x] Subsegment

- [ ] Sampling Document 

- [ ] Annotation


### Question 15

At which point of the flow in a method execution in Amazon API Gateway can you add a Cognito User Pool, Lambda or IAM authorizer?

- [ ] Integration Request

- [ ] Method Request

- [ ] Method Response

- [ ]Integration Response