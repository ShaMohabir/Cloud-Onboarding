## Cloud Summary

- Cloud computing is a term used to refer to Internet based development and services

- A number of characteristics define cloud data, applications services and infrastructure:
    - Remotely hosted: Services or data are hosted on remote infrastructure
    - Present: Services or data are available from anywhere
    - Value: You can for what you want and use

## Cloud Computing Modules

- **Software as a Service (SaaS)**: Software licensing and delivery model in which software is licensed on a subscription basis and is centrally hosted 

- **Platform as a Service (PaaS)**: Provides a platform allowing customers to develop, run, and manage applications without the complexity of building and maintaining the infrastructure

- **Infrastructure as a Service (IaaS)**: Provides virtualized computing resources over the internet

## Cloud Platforms

- **Amazon Web Services (AWS)**: The oldest and most experienced player on the market – it has 11 years in operation (established at the beginning of 2006). AWS has an extensive list of computing services with functions of deployment, mobile networking, and others

    To learn more about AWS and to get a hands-on experience with their console, visit [AWS Portal](https://portal.aws.amazon.com/)

- **Microsoft Azure**: Presented in February 2010, and since then it has shown a great promise among its rivals. This platform can easily be associated with AWS, both of them provide their custom with a full set of services

    To learn more about Azure and to get a hands-on experience with their console, visit [Azure Portal](https://portal.azure.com/)

- **Google Cloud Platform (GCP)**: Started their journey on October 6. 2011. For now, they’ve had 5 years during which they’ve managed to create a good presence in the industry. Initially, the push was done to strengthen their own services such as Google or YouTube. But they went further and created enterprise services – now anyone can use their cloud platform

    To learn more about Azure and to get a hands-on experience with their console, visit [Google Cloud Portal](https://cloud.google.com/cloud-console/)

## Cloud Open Source Tools

1.) **Visual Studio Code** - Combines the simplicity of a source code editor with powerful developer tooling, like IntelliSense code completion and debugging.  It allows the user to edit-build-debug with ease 
     
- To learn more about VS Code, review [Visual Studio Code Tutorial](https://www.youtube.com/watch?v=fnPhJHN0jTE/)

2.) **Github & Git** - Github is a Code hosting platform for version control and collabaration and Git is a version control management tool
 
- To learn more about Github and Git, review [Github & Git Tutorial](https://www.youtube.com/watch?v=xuB1Id2Wxak)

3.) **Ansible** - An IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs.  Designed for multi-tier deployments, Ansible models your IT infrastructure by describing how all of your systems inter-relate, rather than just managing one system at a time

- To learn more about Ansible, review [Ansible Playbook Tutorial](https://www.youtube.com/watch?v=dCQpaTTTv98) 

4.) **Jenkins** - A software that allows continuous integration. Jenkins will be installed on a server where the central build will take place.  **What is Continuous Integration?** it's a development practice that requires developers to integrate code into a shared repository at regular intervals. This concept was meant to remove the problem of finding later occurrence of issues in the build lifecycle. Continuous integration requires the developers to have frequent builds. The common practice is that whenever a code commit occurs, a build should be triggered

- To learn more about Jenkins, review [Jenkins Tutorial](https://www.youtube.com/watch?v=Lxd6JMMxuwo&t=121s)

- To learn about Jenkins Multi-branch, review [Jenkins Multi-Branch Pipeline](https://www.youtube.com/watch?v=uVXO95syoEg)

**Jenkins cheat sheet**
- Installing Jenkins on an EC2/VM (Note: Since your instance will not running 24/7 and you don't have a static ip, you'll want to map your jenkins volume to your local machine/host.  In real world scenario, you won't need to do this.)

1.) Make directory (mkdir) jenkins (or speficic name)

2.) Change folder permission sudo chown -R 1000:1000 /home/ubuntu/jenkins (this is name and path of the folder)

3.) Mapping jenkins volume onto host (local machine) and installing jenkins: 
- docker run -p 8080:8080 -v /home/ubuntu:/var/jenkins_home jenkins

5.) **Docker** - 
6.) **Kubernetes** - 


