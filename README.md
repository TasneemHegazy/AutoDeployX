## AutoDeployX

Welcome to the AutoDeployX project repository! This repository showcases my proficiency in Continuous Integration and Continuous Deployment (CI/CD) techniques for achieving automated build and deployment of cloud-based software products.

### Purpose

The purpose of this repository is to demonstrate my skills and knowledge in the following areas:

- Explaining the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Designing and building CI/CD pipelines that support Continuous Delivery processes, utilizing Deployment Strategies.
- Utilizing a configuration management tool to accomplish deployment to cloud-based servers.
- Utilizing centralized structured logging to surface critical server errors for diagnosis.

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)

- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [URL01]
  1. Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02]![Alt text](URL02_SCREENSHOT-1.png)
  1. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03]![Alt text](URL03_SCREENSHOT-1.png)
  1. Public URLs to deployed application back-end in EC2 [URL04]![Alt text](URL04_SCREENSHOT-1.png)
  1. Public URL to your Prometheus Server [URL05]![Alt text](URL05_SCREENSHOT-1.png)
- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions. These screenshots should be included in your code repository in the root folder.
  1. Job failed because of compile errors. [SCREENSHOT01]![Alt text](SCREENSHOT01-1.png)
  1. Job failed because of unit tests. [SCREENSHOT02]![Alt text](SCREENSHOT02-1.png)
  1. Job that failed because of vulnerable packages. [SCREENSHOT03]![Alt text](SCREENSHOT03-1.png)
  1. An alert from one of your failed builds. [SCREENSHOT04]![Alt text](SCREENSHOT04-1.png)
  1. Appropriate job failure for infrastructure creation. [SCREENSHOT05]![Alt text](SCREENSHOT05-1.png)
  1. Appropriate job failure for the smoke test job. [SCREENSHOT06]![Alt text](SCREENSHOT06-1.png)
  1. Successful rollback after a failed smoke test. [SCREENSHOT07]  ![Alt text](SCREENSHOT07-1.png)
  1. Successful promotion job. [SCREENSHOT08]![Alt text](SCREENSHOT08-1.png)
  1. Successful cleanup job. [SCREENSHOT09]![Alt text](SCREENSHOT09-1.png)
  1. Only deploy on pushed to `master` branch. [SCREENSHOT10]![Alt text](SCREENSHOT10-1.png)
  1. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11]![Alt text](SCREENSHOT11.1-1.png)
  1. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12]![Alt text](SCREENSHOT12-1.png)


### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
