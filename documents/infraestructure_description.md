# Infrastructure of the project

This project use the AWS Cloud as Infrastructure as a Service (IaaS).


## Infrastructure Diagram
(IMG)

![](https://github.com/jaguilarweb/udagram-updated/blob/master/documents/infraestructure-diagram.png)

The diagram avobe includes the different AWS services used for hosting the API, Frontend, and the DB.


## AWS Elastic Beanstalk

AWS Elastic Beanstalk is a service (platform as a service) that allows you to run your web application on the AWS cloud without worrying about scaling or configuring the underlying virtual machines (web servers).

This application create the following resources as part of the environment:

- An EC2 instance to host your application
- A security group (firewall rules) for the EC2 instance
- An S3 bucket to store the application artifacts
- A CloudWatch alarm for logging and monitoring
- A domain name


### Frontend hosting Amazon S3

Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.

I used Amazon S3 to host the frontend developed in Angular.

### Backend (API) hosting Amazon EC2

Amazon EC2 provides the broadest and deepest instance choice to match your workload’s needs. General purpose, compute optimized, memory optimized, storage optimized, and accelerated computing instance types are available that provide the optimal compute, memory, storage, and networking balance for your workloads.


### Database hosting Amazon RDS

Amazon Relational Database Service  is a collection of managed services that makes it simple to set up, operate, and scale databases in the cloud.

In this case I used with engine PostgreSQL.
