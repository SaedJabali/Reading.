# Amazon Cognito

It is an Amazon Web Services product that controls user authentication and access for mobile applications on internet-connected devices.

It collects a user's profile attributes into directories called user pools that a mobile app or web app uses to configure limited access to AWS resources. An identity pool consolidates end-user information, which client access platforms, devices and operating systems receive to organize federated identity groups.

### Cognito Usage

Cognito enables simple, secure user authentication, authorization and user management for web and mobile apps.


#### Usage

1. Easily add user sign-up, sign-in and access control to their apps with its built-in user interface (UI) and easy configuration

2. Synchronize data across multiple devices and applications
3. Provide secure access to other AWS services from their app by defining roles and mapping users to different roles
4. Federate identities from social identity providers

### User pools vs. identity pools

* User pools: user directories that provide sign-up and sign-in options for app users.

* Identity pools: cognito elements grant users access to other AWS services (e.g., Amazon S3 and DynamoDB).

### How cognito authentication works

it works upon these four steps process
1. User signs in through a user pool.
2. Once successfully authenticated, they receive a user pool token.
3. The app exchanges the token for AWS credentials through an identity pool.
4. User can use these authenticated AWS credentials to access other services in the AWS cloud. 

![working](https://cdn.ttgtmedia.com/rms/onlineimages/aws-excerpt_cognito.png)