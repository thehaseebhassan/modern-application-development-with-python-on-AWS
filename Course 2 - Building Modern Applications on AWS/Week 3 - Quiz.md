# Building Modern Python Applications on AWS - Coursera

## Week 3 - Quiz

### Question 1

Which mechanism allows you to control who has access your AWS Lambda function and what actions they are allowed to perform?

- [ ] IAM Groups

- [ ] Execution Permissions

- [x] Resource Based Policies

- [ ] IAM Policies


### Question 2

AWS Lambda has two main different types of triggers. Triggers that push events to Lambda, like other AWS services or applications you develop, and triggers that are a resource that Lambda reads items from, like a stream or queue, and invokes a function based on a configuration that you create. 

What is the second type of trigger called?

- [ ] Lambda Source Mapping

- [x] Event Source Mapping

- [ ] Pull Resource Configuration

- [ ] Push Trigger


### Question 3

What is the maximum timeout or maximum amount of time for the execution of a Lambda function?

- [ ] 5 minutes

- [x] 15 minutes

- [ ] 5 hours

- [ ] 15 hours


### Question 4

What is the type of runtime that would need to be used to use PHP for the code running in Lambda?

- [x] Custom runtime

- [ ] Lambda layers

- [ ] PHP 7.x runtime

- [ ] You can’t run PHP in Lambda


### Question 5

Which of the following is a good use case for using the Provisioned Concurrency feature of Lambda?

- [ ] The application needs to run once per hour.

- [x] The application is made up of latency-sensitive microservices.

- [ ] The application is a batch processing tool.

- [ ] The application needs access to a relational database.


### Question 6

When the application code in a Lambda function needs to communicate with a relational database, which feature of the AWS Lambda service would minimize the amount of connections to that relational database?

- [x] Execution context reuse

- [ ] Provisioned Concurrency

- [ ] Automatic scaling

- [ ] Synchronous invocation


### Question 7

What are the two ways that a Lambda function can be invoked? Select two.

- [ ] Reduced-latency

- [ ] Provisioned concurrency

- [x] Asynchronously

- [x] Synchronously

- [ ] Automatically


### Question 8

If retry attempts is configured with the default setting on a Lambda function, what do you need to make sure you do in your code?

- [x] Make sure that your code is idempotent.

- [ ] Make sure that there are no global variables in the code.

- [ ] Make sure that the code can be executed concurrently.

- [ ] Make sure that any transactions on the database are committed.


### Question 9

In AWS Lambda, what are you responsible for managing?

- [ ] Backend Infrastructure

- [ ] Operating System Updates

- [x] Function Code

- [ ] Operating System Patches


### Question 10

Per the AWS shared responsibility model, who is responsible for the protection of customers’ data?

- [ ] Third-party security auditor

- [ ] AWS

- [ ] SFD

- [x] The customer
