# Building Modern Python Applications on AWS - Coursera

## Week 1 - Quiz

### Question 1

When you access AWS programmatically, you use an access key to verify your identity and the identity of your applications. When programming using the AWS SDK locally on your personal computer, which method should you use for supplying AWS credentials?

- [ ] Hard coding the credentials into the code

- [ ] Configure the AWS Credentials file to contain an access key id and secret access associated with an IAM User

- [ ] Use Temporary Role Based Access using IAM Roles

- [x] Configure the AWS Credentials file to contain a username and password associated with an IAM User

### Question 2

What are the three common ways you can interact with the APIs of AWS?

- [ ] Access Key and Secret Key, HTTP and Cloud9

- [x] AWS Management Console, CLI and SDK

- [ ] HTTPS, IAM Role, Telnet

- [ ] DNS, HTTP, Username and Password

### Question 3

In Cloud9, how often are the AWS managed temporary credentials automatically rotated?

- [x] Every 5 minutes

- [ ] Every 5 days

- [ ] Every 5 seconds

- [ ] Every 5 hours

### Question 4

Which file contains your credentials that the CLI uses to make calls AWS on Cloud9 or from your laptop?

- [ ] .aws/config

- [ ] .aws/creds

- [x].aws/credentials

- [ ] .aws/keys

### Question 5

What command can you use to have more information about the S3 list bucket CLI command?

- [ ] aws ls help

- [ ] help aws ls

- [ ] help aws s3 ls

- [x] aws s3 ls help

### Question 6

AWS Cloud9 operates as what kind of cloud-based environment?

- [ ] Independent Deployment Environment

- [x] Integrated Development Environment

- [ ] Irreplaceable Development Environment

- [ ] Infrastructure Deployment Environment

### Question 7

What does the AWS Serverless Application Model template specification provide to help deploy your serverless application on AWS?

- [ ] A drag-and-drop console for developing serverless applications

- [ ] A prebuilt application template for all application types

- [x] Shorthand syntax to express functions, APIs, databases, and more in a declarative way

- [ ] An Amazon EC2 instance to deploy your application code

### Question 8

Which of the following is NOT one of the steps to use an IAM Role instead of using the AWS managed temporary credentials in Cloud9?

- [ ] Create an IAM Role with an IAM Policy

- [ ] Disable AWS managed temporary credentials

- [x] Add access key and secret key to credentials file

- [ ] Attach IAM Role to the Cloud9 EC2 instance

### Question 9

What is considered a best practice for providing AWS credentials to your code using the AWS SDK running?

- [ ] Hard-coding credentials

- [ ] Using environment variables

- [ ] Storing the credentials in a file

- [x] Using IAM Roles
