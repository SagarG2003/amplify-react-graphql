# Build a Full Stack React App using AWS Amplify

AWS Amplify provides a Git-based CI/CD workflow for building, deploying, and hosting single-page web applications or static sites with serverless backends. Upon connecting to a Git repository, Amplify determines the build settings for both the frontend framework and any serverless backend resources configured with the Amplify CLI, and automatically deploys updates with every code commit.

~ Hosting: Build and host a React application on the AWS global content delivery network (CDN).

~ Authentication: Add auth to your app to activate sign-in and sign-out.

~ Database and storage: Add a GraphQL API, database, and storage solution.

## AWS Service used in the project 

1) AWS Amplify: Used for hosting react app with serverless backends adn automated CI/CD pipelining.

2) AWS Cognito:  Allows users to sign in and authenticate to the websites. It also provides temporary security credentials to access app backend resources. Multi Factor Authentication is also used in this project to provide extra layer of security.
   
3) AWS DynamoDB: Used for backened of the project. Its a NoSQL database service hat provides fast and predictable performance with seamless scalability. With DynamoDB, you can create database tables that can store and retrieve any amount of data and serve any level of request traffic.
   
4) Amazon S3: Used for storing and querying for files, such as images and videos. Storage services like Amazon S3 exist to make this as easy, performant, and inexpensive as possible.

5) GraphQL API: A query language and server-side API implementation based on a typed representation of your application. This API representation is declared using a schema based on the GraphQL type system.

## System Architecture

![amplify1](https://github.com/SagarG2003/amplify-react-graphql/assets/113847560/4cb16ed5-1095-407d-bf04-b37e60324a82)

## Steps 




