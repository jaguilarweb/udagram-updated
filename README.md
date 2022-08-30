# Hosting a Full-Stack Application Udagram

## Overview

The project application, Udagram - an Image Filtering application, allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering service. It has two components:

Frontend - Angular web application built with Ionic framework
Backend RESTful API - Node-Typescript application

The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.


### Screenshot

(OF the working application)

- The last successful CircleCi build
(Supply diferent screenshot for phases - build, hold, deploy)

- AWS RDS for the database
- AWS ElasticBeanstalk for de (backend) API deployment.
- AWS S3 for (frontend) web hosting

### Arquitecture Diagram (high level overview of the infraestructure)




## Links to host


## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)


## Disclaimer
- Disclaimer: This is a learning proposal or test project and your use of the code is under your own accountability.

- Trademarks: Any of the trademarks, service marks, collective marks, design rights, personality rights or similar rights that are mentioned, used or cited in this project are the property of their respective owners. Their use here does not imply that you may use them for any other purpose other than for the same or a similar informational use as contemplated by the original authors.

## Author
 Udacity provides the case and Jenny Aguilar (@jaguilarweb) suggests the solution.