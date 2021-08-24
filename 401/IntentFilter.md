# Intent Filter

It is an expression in the app’s manifest file, and it is used to specify the type of intents that the component would 
like to receive.

The intent filter can be nested in the app components, and we can specify the type of intents to accept using these three elements.

1. <action/ >

It defines the name of an intended action to be accepted, and it must be a literal string value of an action, not the class constant.

2. <category/ >

It defines the name of an intent category to be accepted, and it must be the literal string value of an action, not the class constant.

3. <data/ >

It defines the type of data to be accepted and by using one or more attributes we can specify various aspects of the data URI (scheme, host, port, path) and MIME type.

We can put multiple intent filters in manifest file

![filters](https://i.stack.imgur.com/w3iKL.png)

