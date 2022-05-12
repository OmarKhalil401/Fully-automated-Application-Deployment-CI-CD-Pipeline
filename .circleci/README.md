

## CircleCI Config.yml

The Config.yml file contains all of the project's pipeline jobs and workflow

###  workflow jobs

The project contains of 15 main jobs:

1- Buiding Frontend and Backend code.

2- Testing the build of Frontend and Backend code.

3- scanning Frontend and Backend code for vulnerabilities.

4- Deploying Infrastructure on AWS using CloudFromation templates.

5- configuring Infrastructure using Ansbile playbooks.

6- Running Migrations from local to Postgres Database.

7- Deploying Backend from local machine to EC2 using Ansbile.

8- Deploying Frontend to S3 bucket.

9- Smoke testing our Infrastructure.

10- promeoting to CloudFront Distribution.

11- cleaning up the old deployment Infrastructure after swaping to our green enviroment.

12- Rolling back and destroying Infrastructure in case of deployment errors.

13- reverting migrations in case of migration errors.

14- Using commands to facilitates our workflow.

15- Notifyin on Success using CircleCI Orbs.
