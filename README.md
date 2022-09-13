# Complete-CI-CD-Pipeline-with-Jenkins


A Scripted **Multi-branch pipeline** that is triggered automatically on code changes (Using GitHub WebHooks),and which test and build the application ( Java Maven App ) into a docker image with automatically incremented version and push that image into configured docker repo 

![](Images/CI-CD-Pipeline.png)



Steps Of Project :

Step One

- Configure and Start an AWS EC2 for Jenkins ( Managing Instance Security Rules and open port 22 for SSH Conn and 8080 for Jenkins).
- Access EC2 Instance through SSH using CLI.
- Install Docker on Jenkins-Server.
- Start Jenkins as a Docker Container.
- Make Docker Available in jenkins container by mounting docker runtime dir from ec2-instance into jenkins docker container as a volume.




Built With 

- [Amazon AWS EC2-Instance](https://aws.amazon.com/) Cloud services
- [Jenkins](https://www.jenkins.io/) (CI/CD) automation software
- [Docker & docker-compose](https://www.docker.com/) Containerization Tool
- [DockerHub](https://hub.docker.com/) Container Registry
- [GitHub WebHooks](https://docs.github.com/en/developers/webhooks-and-events/webhooks/about-webhooks) User-defined HTTP callbacks
- [Maven](https://maven.apache.org/) Open-source build tool for Java
