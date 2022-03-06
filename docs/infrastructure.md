## Udagram Infrastructure description

![Architecture](./images/architecture.png)

## AWS Services

**RDS Postgres || AWS Relational Database Service**

- The application server uses AWS RDS Postgres as database for storing and retrieving information.

- RDS is a managed service from AWS using which you can set up, operate and scale a relational database in the cloud easily

<!-- - [AWS RDS URL](https://aws.amazon.com/rds/) - Amazon Relational Database Service (RDS)
- [Creating a PostgreSQL DB instance](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_GettingStarted.CreatingConnecting.PostgreSQL.html#CHAP_GettingStarted.Creating.PostgreSQL) - Creating a PostgreSQL DB instance -->

\
**AWS EB || Elastic Beanstalk**

- The application server is deployed on AWS Elastic Beanstalk service.
- provides the backend hosting

  > Elastic Beanstalk provisions and operates the infrastructure and manages the application stack

  > Elastic Beanstalk will create all infrastructure components necessary to operate a web application or service

\
**AWS S3 || Simple Storage Service**

- The frontend application is deployed using AWS S3 Bucket.
- place where the backend saves uploaded media && The bundled assets are uploaded to an S3 bucket

  > Store both static and dynamic assets such as user-generated content (images), backup files
