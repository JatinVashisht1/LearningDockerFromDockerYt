# Getting started with docker and docker desktop.
---

- when you install docker desktop, you will find your self with the following test command to make a container.
```
docker run -d -p 80:80 docker/getting-started
```
- Let's break-down what's the meaning of above command.
- `-d` attribute is used to tell docker to run the command as a detached process, i.e, as a **background** process.
- `-p` is used to **map the port** 80 of local machine to port 80 of **container**.
---
## Let's test the command
- Open the terminal and run the command mentioned in the welcome screen or in the above section.

### What happened after we run the command?
- You can read the message that docker is unable to find the **image** locally, so now it will try to find the image from [docker-hub](https://hub.docker.com/).
- You can find the getting started image on docker hub by clicking [here](https://hub.docker.com/r/docker/getting-started)
- You can see a docker container running on the docker desktop container page.
- Docker has given it a name by its own.
- You can see details by clicking on the name of docker container.
- You can click on the **port number**, i.e, 80:80 in this case to open it on the browser.