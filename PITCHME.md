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

### What is docker

Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package. By doing so, thanks to the container, the developer can rest assured that the application will run on any other Linux machine regardless of any customized settings that machine might have that could differ from the machine used for writing and testing the code.

Refer from:  https://opensource.com/resources/what-docker

---

### Why use docker

- It allow you to including dependencies and environmnet starting from special os components to details such as a special lib versions (Build with Dockerfile)
- It make sure this environment can be shared and run anywhere supports docker, and running result are reproducable.(Share with docker registry)

---

### Difference between docker and virtual machine

![docker-vs-vm](https://www.aquasec.com/wiki/download/attachments/2854029/docker-birthday-3-intro-to-docker-slides-18-638.jpg?version=1&modificationDate=1515522843003&api=v2)

- Docker is light than VM. (hundreds MB compare to VM couple of GB)
   - Start/stop quicker.
   - Smaller size.

---

### Docker Architecture

![docker-architecture](https://www.aquasec.com/wiki/download/attachments/2854029/Docker.JPG?version=1&modificationDate=1515349366681&api=v2)

- Docker Client: This is how you interact with your containers. Call it the user interface for Docker.
- Docker Objects: These are your main components of Docker (Run on dockerhost)
    - containers placeholders for your software, can read and write.
    - images are read only and can be used to create new containers.
- Docker Daemon: A background process responsible for receiving commands and passing them to the containers via command line.
- Docker Registry: Commonly known as Docker Hub, in our case is gitlab, this is where our container images are stored and retrieved.

### Introduction for online docker classroom

- Register an docker account on https://cloud.docker.com/
- Learn dev or ops class from  https://training.play-with-docker.com/
- Start with the dev or ops session.
- Install local can refer: 
    - ubuntu: https://docs.docker.com/install/linux/docker-ce/ubuntu/
    - windows: https://docs.docker.com/docker-for-windows/install/

---

### Questions & Answer

- Q/A

