# Exploring [Docker-Hub](https://hub.docker.com/)

## Downloading the image.
---
- Let's us for example want to use fedora image.
- Simply search for fedora and click on the result with most downloads.
- Here you will see following command
```
docker pull fedora
```
- It is used to pull the fedora image to your local machine.
- This will **not** download the full fedora OS that is around 2 giga bytes.
- It will download the base version to just keep the things running.
- Run the above mentioned command into your terminal.
- You will find the fedora image in the **images** section of docker desktop.

## Running image.
- Lets print **hello world** with docker.
- To run our image run following command
```
docker run fedora echo hello world
```
- This will run fedora image downloaded and print "hello world" on terminal.

- You can explore more options by running `docker --help` command and `docker run --help`.
---
### Exploring docker commands.
- We can use `-t` or `--tty` option with `docker run` to access terminal of the container.
- We can also use `-i` or `--interactive` option with `docker run` to keep the STDIN (standard input) open even if docker container exits.
- Run the following command
```
docker run -t -t fedora
```
- Now you will be able to access the terminal of the docker container, also the docker container will be marked as running.

## Docker container vs docker image.
- Docker **image** is like a blue print to the docker container.
- Docker **container** is the runtime of the image.
- Each time you fire up command to run docker image like *docker run fedora* it will create a new container out of that image.
- You can reuse the docker containers and all of your previous work will be stored there.
- Changes in one container will not affect the working of another whether they are derived from same image or not.
