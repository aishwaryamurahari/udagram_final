# Udagram Infrastructure Overview

Udagram is a cloud-based application with two core components:

1. **udagram-api**: A RESTful API designed to cater to incoming Feed and User requests.
2. **udagram-frontend**: A user interface developed using Angular that communicates with the `udagram-api`.

## Deployment on AWS

- **FrontEnd**: Udagram's front-end interface is hosted on **AWS S3**.
- **BackEnd**: The back-end service, `udagram-api`, is deployed via **AWS Elastic Beanstalk**.
- **Database**: Data persistence is achieved through a **PostgreSQL database** managed by **AWS RDS**.
