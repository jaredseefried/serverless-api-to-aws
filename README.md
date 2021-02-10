# Note Application API - Serverless Framework tp AWS

## Table of Contents

- **[Description](#Description)**
- **[Installation Requirements](#Installation-Requirements)**
- **[License](#License)**
- **[Questions](#Questions)**

# Description
The Note Application API is a Serverless stack integrated with AWS Cloud Services. The Serverless Framework uses AWS Lambda and API Gateway to create the back end and deploys the Lambda functions, along with the AWS infrastructure resources they require. the serverless.yml file contains the configuration on what AWS services Serverless will provision and how to configure them. CRUD REST API's are created to perform the necessary operations with AWS DynamoDB. We also set up an S3 bucket for file storage. AWS Cognito User Pools and Identity Pools, IAM Roles and are created for user authentication using AWS Amplify. Stripe is created for the billing API. 

 ### Deployed Site @ https://my-serverless-note-app-to-aws.netlify.app/
---
 ![Scratch Note App](./resources/images/architecture.jpg)

# Installation Requirements

1. Clone Note Application in the command line by entering: git clone https://github.com/jaredseefried/serverless-api-to-aws.git

2. Install required libraries from entering in the command line: npm i

3. Update .env file with required information. 

5. Start the application by entering in the command line: npm start

If you would like to learn how to build this application from scratch, follow this tutorial: https://serverless-stack.com/chapters/what-is-serverless.html 
# License

MIT

# Have Questions?

## [Github Profile: github.com/jaredseefried](https://github.com/jaredseefried "Title")

Please email me at jared.seefried@yahoo.com if you have additional questions.