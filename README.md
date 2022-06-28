# Building Modern Node.js Applications on AWS
In modern cloud native application development, it’s oftentimes the goal to build out serverless architectures that are scalable, are highly available, and are fully managed. This means less operational overhead for you and your business, and more focusing on the applications and business specific projects that differentiate you in your marketplace. In this course, we will be covering how to build a modern, greenfield serverless backend on AWS. 

Building brand new applications on AWS is a different task than lifting and shifting existing applications into AWS. When you have an existing application that you need to move to AWS, you might first look to using Amazon EC2 as your virtual machines, or maybe you might look into using docker containers and container hosting services like Amazon Elastic Container Service or Amazon Elastic Kubernetes Service. Those are all great application hosting options, but in most cases, they still require you to have some kind of pulse on the underlying infrastructure hosting your application. 	`

Building Modern Node.js Applications on AWS will explore how to build an API driven application using Amazon API Gateway for serverless API hosting, AWS Lambda for serverless computing, and Amazon Cognito for serverless authentication. We will follow an API driven development process and first mock up what the API will look like. We will cover all the ins and outs of the service Amazon API Gateway, and as you’ll learn- it does a lot more than just hosting an API. 

Exercise 1: Setting Up and Exploring the SDK

In this exercise, you install and configure the AWS Command Line Interface (AWS CLI) and the AWS SDK for JavaScript in Node.js. After you install the necessary requirements, you create an S3 bucket and deploy a web application to the bucket. You then set up data in Amazon S3, and configure AWS Systems Manager parameters for the Dragons application. After you create all the resources, you explore the JavaScript application.

Exercise 2: Amazon API Gateway

In this exercise, you build the REST API that’s used to list and add dragons. You first create the API by using mock integrations. You can use mock integrations to create a testable API before any code is written for your backend services.

After the API is created, you deploy an updated version of the web application. The web application now contains the frontend logic to access the GET and POST methods of your /dragons resource.
