# JenkinsCI-NEXUS-ECR
Continuous integration project with Jenkins building and containerizing an image to save in the __Nexus repository__ or in __AWS ECR__.
![Untitled Diagram](https://github.com/user-attachments/assets/e7506523-b424-49b5-a40a-78e766643c9b)


This project leverages Jenkins as a Continuous Integration (CI) tool, __Git__ to retrieve the code from a __GitHub__ repository, and __Maven__ to compile the code and run unit tests. __SonarQube__ is used to analyze the code for potential threats or vulnerabilities. After the application is containerized, it is pushed to either a local __Nexus__ repository or __AWS Elastic Container Registry (ECR)__.

In the following repository, you'll find scripts to install the mentioned tools and the Groovy code for the defined pipelines:

- __Repo-ECR:__ Pushes the container image to the AWS ECR repository.
- __Repo-Nexus:__ Pushes the container image to the local Nexus repository.
  
This setup automates the process from code retrieval and compilation to analysis, testing, containerization, and deployment to repositories.

# Pipeline run results:

__Nexus Repository__

![A-NEXUS](https://github.com/user-attachments/assets/9679b1b9-6e80-4dba-8ab2-8d8ad44eeeb0)
![NEXUS](https://github.com/user-attachments/assets/8a51db5a-ee67-4f86-8ec9-3f520eb47280)
![NEXUS2](https://github.com/user-attachments/assets/3f09c61a-c274-4487-9854-0cc66a2e4f7e)


__Amazon ECR__

![Screenshot from 2025-03-05 23-06-41](https://github.com/user-attachments/assets/dfa83abd-166a-4e6a-82a3-45a236eb5e21)
![ECR2](https://github.com/user-attachments/assets/fa68dd36-8ab4-454a-9a5c-7813cdce2554)
![ECR-1](https://github.com/user-attachments/assets/f86f66cf-55c8-4425-af83-bb9dd203b6f4)
