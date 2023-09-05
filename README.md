# Java Web Application on Apache Tomcat Server



## Description

This project is a Java-based web application that demonstrates the deployment of a web application on an AWS EC2 instance using the Tomcat web server.
In This Project we have used Jenkins Tool to automate the process of Building and Deployment.


![Deployment_on_Tomcat](https://github.com/ShubhamBhurse/Project-1_Application_Deployed_On_Tomcat/assets/130531451/555fb332-0e21-4aba-bf6e-58b95e036d64)


## Project Video



https://github.com/ShubhamBhurse/Project-1_Application_Deployed_On_Tomcat/assets/130531451/26b7a8b0-394f-4c32-9129-16aedbff46e3



## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
3. [Deployment](#deployment)
4. [Usage](#usage)
5. [AWS Services](#aws-services)
6. [Jenkins Automation](#jenkins-automation)
7. [Source Code](https://github.com/ShubhamBhurse/maven-web-application.git)
8. [Acknowledgments](#acknowledgments)
9. [Contact Information](#contact-information)

## Prerequisites

- Java 11 or higher
- Apache Tomcat 9.0 or higher
- AWS account with EC2 access

## Installation

1. Clone the repository: `git clone https://github.com/ShubhamBhurse/maven-web-application.git`

2. Build the project: `mvn clean install`

## Deployment

To deploy this application on AWS:

1. Launch an EC2 instance.
2. Install and configure Tomcat on the EC2 instance.
3. Deploy your WAR file to Tomcat webapps directory.
4. Configure any necessary environment variables.

## Usage

- Access the application at `http://52.66.198.215:8080/maven-web-application`.

## AWS Services

- This project utilizes AWS EC2 for hosting the application.
- IAM roles and security groups are configured for security.

## Jenkins Automation

This project includes automated building and deployment using Jenkins CI/CD pipelines. Here's how it works:

1. **Continuous Integration (CI):** Jenkins automatically builds the project whenever changes are pushed to the repository.

2. **Continuous Deployment (CD):** Jenkins deploys the latest build to the AWS EC2 instance running Tomcat whenever changes are merged into the main branch.

To set up Jenkins for this project, follow these steps:

1. Install Jenkins on EC2 Instance.

2. Configure Jenkins to monitor your project's repository.

3. Set up build and deploy pipelines using Jenkinsfile or configure Jenkins jobs.

## Source Code
[Click Here](https://github.com/ShubhamBhurse/maven-web-application.git)

## Acknowledgments
Source Code is devloped by MSS (Mithun Software Solutions)
Thanks to the MSS community for their excellent Code.

## Contact Information

For questions or support, please contact

Name : Shubham Bhurse

Email : shubhbhurse900@gmail.com
