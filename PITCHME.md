# Docker Session

Docker Session 1

---

### Agenda 

- What is docker and why use docker
- Difference between docker and virtual machine.
- Docker Architecture
- Introduction for online docker classroom
- Q/A

---

#### What is docker

- Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. 
- Refer from:  https://opensource.com/resources/what-docker

---

#### Why use docker

- It allow you to including dependencies and environmnet starting from special os components to details such as a special lib versions (Build with Dockerfile)
- It make sure this environment can be shared and run anywhere supports docker, and running result are reproducable.(Share with docker registry)

---

#### Difference between docker and virtual machine

![docker-vs-vm](https://www.aquasec.com/wiki/download/attachments/2854029/docker-birthday-3-intro-to-docker-slides-18-638.jpg?version=1&modificationDate=1515522843003&api=v2)
- Docker is light than VM. (hundreds MB compare to VM couple of GB)
   - Start/stop quicker.
   - Smaller size.

---

#### Docker Architecture - Docker Client

![docker-architecture](https://www.aquasec.com/wiki/download/attachments/2854029/Docker.JPG?version=1&modificationDate=1515349366681&api=v2)
- Docker Client: This is how you interact with your containers. Call it the user interface for Docker.

---

#### Docker Architecture - Docker Objects

![docker-architecture](https://www.aquasec.com/wiki/download/attachments/2854029/Docker.JPG?version=1&modificationDate=1515349366681&api=v2)
- Docker Objects: These are your main components of Docker (Run on dockerhost)
    - containers placeholders for your software, can read and write.
    - images are read only and can be used to create new containers.

---

#### Docker Architecture - Docker Daemon

![docker-architecture](https://www.aquasec.com/wiki/download/attachments/2854029/Docker.JPG?version=1&modificationDate=1515349366681&api=v2)
- Docker Daemon: A background process responsible for receiving commands and passing them to the containers via command line.

---

#### Docker Architecture - Docker Registry

![docker-architecture](https://www.aquasec.com/wiki/download/attachments/2854029/Docker.JPG?version=1&modificationDate=1515349366681&api=v2)
- Docker Registry: Commonly known as Docker Hub, in our case is gitlab, this is where our container images are stored and retrieved.

---

#### Introduction for online docker classroom

- Register an free account on https://cloud.docker.com/
- Pick dev or ops class from  https://training.play-with-docker.com/

---

#### Install docker on local PC

Refer:
- ubuntu: https://docs.docker.com/install/linux/docker-ce/ubuntu/
- windows: https://docs.docker.com/docker-for-windows/install/

---

#### Future plan

- Learn classroom at yourselves's good time.
- Ask question about docker in IT Channel.

---

### Questions & Answer

- Q/A
