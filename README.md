# AWS SDK for Java Sample Project

A simple Java application illustrating usage of the AWS SDK for Java.

## Requirements

The only requirement of this application is Maven. All other dependencies can
be installed by building the maven package:
    
    mvn package

## Basic Configuration

You need to set up your AWS security credentials before the sample code is able
to connect to AWS. You can do this by creating a file named "credentials" at ~/.aws/ 
(C:\Users\USER_NAME\.aws\ for Windows users) and saving the following lines in the file:

    [default]
    aws_access_key_id = <your access key id>
    aws_secret_access_key = <your secret key>

See the [Security Credentials](http://aws.amazon.com/security-credentials) page
for more information on getting your keys.

## Running the DynamoDB Streams sample

https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Streams.LowLevel.Walkthrough.CompleteProgram.html

is run it:

    mvn clean compile exec:java


## License

This sample application is distributed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

