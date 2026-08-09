# Java Web App Deployment with AWS CI/CD

This project documents my hands-on journey building a Java web application in AWS and gradually integrating it with DevOps and CI/CD tools.

The project is part of my practical learning in AWS and DevOps, where I am focusing on understanding how development, version control, cloud infrastructure, and deployment workflows connect together.

<br>

## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [What I Have Completed](#what-i-have-completed)
- [Setup](#setup)
- [Challenges and Troubleshooting](#challenges-and-troubleshooting)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Introduction

This project introduces the process of developing and eventually deploying a Java-based web application using AWS and CI/CD tools.

Instead of only learning DevOps concepts theoretically, I am using this project to gain hands-on experience with cloud infrastructure, Linux commands, Git, GitHub, and development tools.

My goals for this project are to:

- Build practical AWS and DevOps skills through hands-on implementation.
- Understand how code moves from a development environment into a version-controlled repository and eventually through a CI/CD pipeline.
- Build a documented cloud project that demonstrates my learning and technical development.

<br>

## Technologies

The project currently uses:

- **Amazon EC2** — Hosts my cloud-based development environment using Amazon Linux.
- **Amazon Corretto 8 (Java)** — Provides the Java environment required for the web application.
- **Apache Maven** — Generates and manages the Java web application project.
- **Visual Studio Code** — Used as my IDE and connected directly to the EC2 instance through Remote SSH.
- **Git** — Tracks changes to the application's source code using version control.
- **GitHub** — Stores the project's source code and Git commit history in a remote repository.

### Coming Soon

As I continue building the CI/CD pipeline, I will also integrate:

- **AWS CodeArtifact** — For managing project dependencies and artifacts.
- **AWS CodeBuild** — For automating the application build process.
- **AWS CodeDeploy** — For automating application deployment.
- **AWS CodePipeline** — For connecting the development, build, and deployment stages into an automated CI/CD workflow.

<br>

## What I Have Completed

So far, I have:

- Launched and configured an Amazon EC2 development instance.
- Connected to the EC2 instance using SSH.
- Installed Java 8 and Apache Maven.
- Generated a Java web application using a Maven archetype.
- Connected VS Code directly to the EC2 instance using Remote SSH.
- Edited the application's `index.jsp` file.
- Installed and configured Git.
- Created a local Git repository for the project.
- Connected the local repository to GitHub.
- Used Git staging, commits, and push operations to manage changes.
- Configured my Git identity for future commits.
- Used a GitHub Personal Access Token for HTTPS authentication.

<br>

## Setup

To clone this repository:

```bash
git clone https://github.com/farahrehana/nextwork-web-project.git
```

Navigate into the project:

```bash
cd nextwork-web-project
```

Install the project dependencies using Maven:

```bash
mvn install
```

<br>

## Challenges and Troubleshooting

This project also gave me experience troubleshooting issues rather than only following the successful path.

Some of the issues I encountered included:

- Troubleshooting EC2 resource limitations while using VS Code Remote SSH.
- Updating the EC2 Public DNS after restarting the instance.
- Configuring Windows permissions for the `.pem` private key used for SSH.
- Configuring Java correctly so Maven could detect the required Java environment.
- Understanding the difference between saving changes locally, committing them with Git, and pushing them to GitHub.
- Resolving GitHub authentication issues by using a Personal Access Token instead of a GitHub account password.

These troubleshooting steps helped me better understand how the different components of the development environment work together.

<br>

## Contact

**Nurul Farah Rehana**

GitHub: [farahrehana](https://github.com/farahrehana)

<br>

## Conclusion

This project is helping me build a practical understanding of AWS, Git, GitHub, Linux, and DevOps workflows by applying each concept in a working environment.

The next stages of the project will expand this setup into a CI/CD pipeline using AWS developer tools.

A big shoutout to [NextWork](https://learn.nextwork.org/app) for providing the project guidance used throughout this learning journey.