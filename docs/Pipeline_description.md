## Pipeline process

# This app intergrate with CircleCI :

- CircleCI trigger the event when code is changed from github. It will process based on the branch your were setting on Circle CI

- Set up environment : This step initializes a fresh environment or container where the build and deployment processes will run.

- Preparing environment variable : This step ensures that all necessary environment variables are set and available for subsequent steps.

- Install Nodejs : This step ensures that Node.js version 14.15 is installed in the environment.

- Setting up Elastic Beanstalk CLI : The Elastic Beanstalk CLI provides a direct method for managing AWS Elastic Beanstalk applications. This step ensures the EB CLI is set up correctly.

- Install AWS CLI : This step ensures that the latest version of the AWS CLI is installed

- Configure AWS Acess Key ID : To perform AWS operations, authentication is needed. This step involves setting up credentials, specifically the AWS Access Key ID, to authenticate and authorize actions with AWS.

- Checkout code : This involves fetching the latest code from GitHub repository and it ensures that the most recent version of the code is used for the build and deployment.

- Install Front-end Dependences : This step ensures that all necessary dependencies for the front-end application are installed, typically using package managers like npm

- Install Back-end Dependences : this step prepares the backend or API. It involves installing necessary packages or dependencies specifically for the backend.

- Front-end Build : This process compiles and bundles the front-end code, optimizing it for production.

- API Build: This step prepares the backend or API for deployment. It involves compiling TypeScript to JavaScript or bundling the application.

- Deploy Front-end app to S3 : Once the front-end application is built, this step deploys it to a hosting environment which is AWS S3.

- Deploy Back-end app to Elastic Beanstalk: this step deploys the backend application to AWS Elastic Beanstalk
