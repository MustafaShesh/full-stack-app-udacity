# Infrastructure

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. 
(https://us-east-1.console.aws.amazon.com/rds/home?region=us-east-1#database:id=database-1;is-cluster=false)

2. In AWS, provision a elasticbeanstalk server for deployed application.
(https://us-east-1.console.aws.amazon.com/elasticbeanstalk/home?region=us-east-1#/applications)

3. In AWS, provision a s3 bucket for hosting the uploaded files. 
(https://s3.console.aws.amazon.com/s3/buckets?region=us-east-1&region=us-east-1)

4. In CircleCI, automating deployment process to the AWS services every time we push

4. AWS architecture diagram.
(https://lucid.app/lucidchart/b2429187-d1d0-4d19-ab95-52abc1b8e120/edit?viewport_loc=32%2C-7%2C2155%2C1140%2C0_0&invitationId=inv_8ec0d6b7-ce79-4303-a1ee-1e02e6d3e376)

5. CircleCI Pipeline diagram
(https://lucid.app/lucidchart/57714687-6b80-4f68-a247-bd5b6deaa471/edit?viewport_loc=-11%2C-11%2C2155%2C1140%2C0_0&invitationId=inv_3e2e6821-1974-4341-9a27-361e4d54f812)