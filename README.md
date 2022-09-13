# Complete-CI-CD-Pipeline-with-Jenkins


A Scripted **Multi-branch pipeline** that is triggered automatically on code changes (Using GitHub WebHooks),and which test and build the application ( Java Maven App ) into a docker image with automatically incremented version and push that image into configured docker repo 

![](Images/CI-CD-Pipeline.png)


Stages Explained : 










Built With 

- [Amazon AWS EC2-Instance](https://aws.amazon.com/) Cloud services
- [Jenkins](https://www.jenkins.io/) (CI/CD) automation software
- [Docker & docker-compose](https://www.docker.com/) Containerization Tool
- [DockerHub](https://hub.docker.com/) Container Registry
- [GitHub WebHooks](https://docs.github.com/en/developers/webhooks-and-events/webhooks/about-webhooks) User-defined HTTP callbacks
- [Maven](https://maven.apache.org/) Open-source build tool for Java
