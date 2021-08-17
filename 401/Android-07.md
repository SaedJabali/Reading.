# Serverless & Amplify

## What is Serverless

Serverless computing is a method of providing backend services on an as-used basis. Servers are still used, but a company that gets backend services from a serverless vendor is charged based on usage, not a fixed amount of bandwidth or number of servers.

Most of the cloud providers have invested in serverless; with the given promotion and realistic offering you can safely assume serverless to be one of the most used cloud services in upcoming years.

### Here are some of the currently available cloud services:

![cloud services](https://miro.medium.com/max/1400/1*YTVgxkvq3YLyHxJi9r1ktw.png)

* AWS Lambda
* Google Cloud Functions
* Azure Functions
* IBM OpenWhisk
* Alibaba Function Compute
* Iron Functions
* Auth0 Webtask
* Oracle Fn Project
* Kubeless

### Functions as a Service (FaaS)
FaaS is an implementation of Serverless architectures where engineers can deploy an individual function or a piece of business logic. They start within milliseconds (~100ms for AWS Lambda) and process individual requests within a 300-second timeout imposed by most cloud vendors.

### Principles of FaaS:
Complete management of servers
Invocation based billing
Event-driven and instantaneously scalable
Key properties of FaaS:
Independent, server-side, logical functions
FaaS are similar to the functions you’re used to writing in programming languages, small, separate, units of logic that take input arguments, operate on the input and return the result.

### Stateless
With Serverless, everything is stateless, you can’t save a file to disk on one execution of your function and expect it to be there at the next. Any two invocations of the same function could run on completely different containers under the hood.

### Ephemeral
FaaS are designed to spin up quickly, do their work and then shut down again. They do not linger unused. As long as the task is performed the underlying containers are scrapped.

### Event-triggered
Although functions can be invoked directly, yet they are usually triggered by events from other cloud services such as HTTP requests, new database entries or inbound message notifications. FaaS are often used and thought of as the glue between services in a cloud environment.

### Scalable by default
With stateless functions multiple containers can be initialised, allowing as many functions to be run (in parallel, if necessary) as needed to continually service all incoming requests.

### Fully managed by a Cloud vendor
AWS Lambda, Azure Functions, IBM OpenWhisk and Google Cloud Functions are most well-known FaaS solutions available. Each offering typically supports a range of languages and runtimes e.g., Node.js, Python, .NET Core, Java.

 ## AWS Amplify

It is a set of tools and services that can be used together or on their own, to help front-end web and mobile 
 developers build scalable full stack applications, powered by AWS. 

Amplify supports popular web frameworks including JavaScript, React, Angular, Vue, Next.js, and mobile platforms 
including Android, iOS, React Native, Ionic, Flutter.

  ## GraphQL Transform

provides a simple-to-use abstraction that helps you quickly create backends for your web and mobile applications on AWS.

You can define your application’s data model using the GraphQL Schema Definition Language (SDL), and the library 
handles converting your SDL definition into a set of fully descriptive AWS CloudFormation templates that implement your data model.
