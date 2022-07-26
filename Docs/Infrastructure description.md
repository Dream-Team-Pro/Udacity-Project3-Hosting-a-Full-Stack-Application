# Hosting a Full-Stack Application

---

# Udagram

This application is provided from Udacity scholarship nanodegree in Advanced Full Stack Web Development as important Project to graduation in that field. 
this project called: a Project3-Hosting-a-Full-Stack-Application.

- Link to access the application: `http://udacity-app-udagram.s3-website-us-east-1.amazonaws.com/`


### Dependencies

```
- Node v16.13.2 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```
### Getting Started

```
- Clone this repo locally from link: git clone https://github.com/Dream-Team-Pro/Udacity-Project3-Hosting-a-Full-Stack-Application.git
- Open project from vscode 
- follow instructions in the Project run & Deploy Locally

```
## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)

```
### Project run & Deploy

- clone project: `git clone https://github.com/Dream-Team-Pro/Udacity-Project3-Hosting-a-Full-Stack-Application.git`
- Go to project root: `cd udagram`
- setup `.env`
- Go to project branch: `cd udgram-api`
- Install dependencies: `npm run install`
- start frontend: `npm run start` 
- Go to project branch: `cd udgram-frontend`
- Install dependencies: `npm run install`
- start frontend: `npm run start` 

```
### AWS services needed for deploy and run the application

Provision the necessary AWS services needed for running the application:
- In AWS, RDS database name: `postgres`
- In AWS, RDS Endpoint: `database-1.ca9emgoopywy.us-east-1.rds.amazonaws.com`
- In AWS, S3 bucket: `udacity-app-udagram` 
- In AWS, elasticbeanstalk Application name: `udagram-cli`
- In AWS, elasticbeanstalk Environment name: `Udagramcli-env`
- In AWS, elasticbeanstalk Application URL: `http://udagramcli-env.eba-k6depxex.us-east-1.elasticbeanstalk.com/` 
- In S3 Bucket website endpoint: `http://udacity-app-udagram.s3-website-us-east-1.amazonaws.com/`
- In AWS, Create IAM Group & user  with permission and credintioans to create and deploy project to Elastik Beanstalk successfully

```
### Environment Variables

POSTGRES_HOST       =   <Database_IP_Address>
POSTGRES_USERNAME   =   <Database_Username>
POSTGRES_DB         =   <Database_Name>  
POSTGRES_PASSWORD   =   <Database_Password>  
DB_PORT             =   <Database_Port>  
PORT                =   4200  
AWS_REGION          =   <us-east-1> 
AWS_PROFILE         =   <Profile>  
AWS_BUCKET          =   <Bucket_Name>
URL                 =   <Url>
JWT_SECRET          =   <Any_Secret>
EB_APP              =   <Application_Name>
EB_ENV              =   <Application_Environment>

```

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

- Go to project root: `cd udagram`
- Go to project branch: `cd udgram-frontend`
- Run: `npm run test`
- Run: `npm run e2e`

```

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.


