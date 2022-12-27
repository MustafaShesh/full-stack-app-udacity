# Full-Stack Application Udacity

---

In this project a newly developed Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers. The aws console to start and configure the services the application needs such as a database to store product information and a web server allowing the site to be discovered by potential customers.

- 

### Dependencies

```
- Node v18.12.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 8.19.2 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Pipeline Steps

1. Preparing environment variables
2. Install NPM
3. Configure AWS Access Keys & region
4. Front-End Install
5. Back-End Install
6. Front-End Build
7. Back-End Build
8. Deploy App


### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. 
(https://us-east-1.console.aws.amazon.com/rds/home?region=us-east-1#database:id=database-1;is-cluster=false)
2. In AWS, provision a s3 bucket for hosting the uploaded files. 
(https://s3.console.aws.amazon.com/s3/buckets?region=us-east-1&region=us-east-1)
3. frontend link. (http://application-1-75139724085.s3-website-us-east-1.amazonaws.com/)
4. From the root of the repo, navigate udagram-api folder `cd reactnd-contacts-server` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.
5. Without closing the terminal in step 1, navigate to the udagram-frontend `cd reactnd-contacts-complete` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.
6. AWS architecture diagram.
(https://lucid.app/lucidchart/b2429187-d1d0-4d19-ab95-52abc1b8e120/edit?viewport_loc=32%2C-7%2C2155%2C1140%2C0_0&invitationId=inv_8ec0d6b7-ce79-4303-a1ee-1e02e6d3e376)

## Testing

This project contains test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd reactnd-contacts-complete`
2. `npm run test`


## Built With

- [React](https://reactjs.org/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License


[License](LICENSE.txt)