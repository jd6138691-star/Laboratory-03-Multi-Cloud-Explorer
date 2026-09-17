# Laboratory 04 - Cloud-Native Engineer

## Mission Overview

This laboratory activity focused on learning the basic concepts of Docker and containerization. I explored how containers differ from traditional Virtual Machines and practiced deploying a web server using Docker. Through the different checkpoints, I learned how to download images, run containers, test applications, and manage the container lifecycle.

## Objectives

The objectives of this laboratory activity were to:

* Understand the difference between Virtual Machines and containers.
* Learn how Docker containers work.
* Practice using basic Docker commands.
* Deploy an Nginx web server using Docker.
* Learn how to start, stop, check, and remove containers.
* Understand how port mapping works.
* Develop basic cloud-native and container management skills.
* Properly document the commands and procedures performed.

## Docker Commands Executed

### Checkpoint 3 - Docker Playground

#### Check Docker Version

```bash
docker --version
```

This command checks if Docker is installed and displays its installed version.

#### Check Docker Environment

```bash
docker info
```

This command displays detailed information about the current Docker environment.

---

### Checkpoint 4 - Deploy Your First Container

#### Download the Nginx Image

```bash
docker pull nginx
```

This command downloads the official Nginx image from Docker Hub.

#### Run the Nginx Container

```bash
docker run -d -p 8080:80 nginx
```

This command runs the Nginx container in the background and connects host port 8080 to port 80 inside the container.

#### Test the Nginx Web Server

```bash
curl http://localhost:8080
```

This command sends a request to the Nginx server and displays its HTML response in the terminal.

---

### Checkpoint 5 - The Container Lifecycle

#### List Running Containers

```bash
docker ps
```

This command shows the Docker containers that are currently running.

#### Stop the Container

```bash
docker stop <container_id>
```

This command stops the selected running container using its container ID.

#### Verify the Container Status

```bash
docker ps -a
```

This command displays all containers and allows the stopped container to be verified.

#### Remove the Container

```bash
docker rm <container_id>
```

This command permanently removes the stopped container from the Docker environment.

## Skills Learned

During this activity, I learned how to use Docker through the command line and became familiar with managing Docker images and containers. I also learned how to deploy an Nginx web server, use port mapping, and test a containerized application using `curl`. In addition, I gained experience with stopping, checking, and removing containers. The activity also improved my understanding of containerization and its role in cloud-native development.

## Challenges Encountered

One challenge I experienced was becoming familiar with the different Docker commands and their functions. I also needed to understand how to identify the correct container ID when stopping and removing a container. Another challenge was understanding how port `8080` on the host connects to port `80` inside the Nginx container. By following the commands carefully and checking the terminal output, I was able to complete the tasks and better understand how Docker containers are managed.
