# Fully automated Database Application Deployment using CircleCi

Through this project, you will be able to Build, Test, and scan the application code as Continues Integration part of the project. Along the way, you will use Continous Deployment Through these steps:

* Deploy Infrastructure using AWS CLI commands and CloudFromation Templates.
* Configure the provisioned backend EC2 instance using Ansible Playbooks and Roles.
* Migrate the Database to an RDS-Postgres database on AWS and integrate it into the provisioned EC2.
* Deploy application Frontend UI and host it on AWS S3 as a static website.
* Deploy application Backend Code on EC2 and open PM2 server on port 3030 using Ansible.
* Smoke Test the whole deployment process to ensure the application is working as intended.
* Promote the application on CloudFront CDN utilizing (Blue/Green) Deployment Strategy.
* Monitor the provisioned EC2 server using a Promethues server and node exporter.
* Sending Alarms by Email based on set of rules and using Promethues Alert Manager.

**Take a closer look at the Whole CI/CD piepleine steps :** 

## Successful Pipeline workflow

![Pipeline](https://i.imgur.com/u6RkWQI.png)

## Project Roadmap

The whole Project's steps are written inside the [.circleci folder.](/.circleci)

<HR>

### Built With

- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool
