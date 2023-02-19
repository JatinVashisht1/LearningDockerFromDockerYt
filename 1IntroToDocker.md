# Introduction to Docker
- Welcome, in this series we will be learning about docker.
- What, why, how. I'll try to answer all these questions.

## Need to learn docker
- In short, using docker to **containarize** our software is a standard practice and help us to keep things running same as they run in our local computer.
- To understand things you can imagine that docker help us to **containarize** our software and make sure it runs same as it run in localhost.
- Most of the modern deployment services allows developers to deploy containers.

### Let's clear the basics.
#### What is a container?
- Quoting from official [docker website](https://www.docker.com/resources/what-container/), *A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.*
- Container abstracts out the dependency of the underlying OS in localhost and simulates the deployment environment while running the application.
#### What is a docker image?
- Again from offical website, *A docker container is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.*
#### Difference between docker image and docker container.
- *Container images become containers at runtime and in case of docker containers, images become containers when they run on Docker Engine.*
- Therefore images when running is called container.