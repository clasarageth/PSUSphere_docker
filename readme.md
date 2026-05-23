# PSUSphere

PSUSphere is a containerized application using Docker and Docker Compose.  
This project allows users to easily build and run the system using a single command.

---


# Requirements

Before running the project, install the following:

* Docker
* Docker Compose

Download Docker:
[https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)

---

# Clone the Repository

```bash
git clone https://github.com/clasarageth/PSUSphere_docker.git
cd PSUSphere_docker
```

---

# Running the Project Locally (Build Image)

This method builds the Docker image from the project files.

```bash
docker-compose up --build
```

After running the command, open:

```plaintext
http://localhost:8000
```

---

# Running the Project Using DockerHub Image

Go to the `for_client` folder:

```bash
cd for_client
```

Run the container:

```bash
docker-compose up
```

This method pulls the image directly from DockerHub.

---

# Docker Commands

## Stop Containers

```bash
docker-compose down
```

## Rebuild Container

```bash
docker-compose up --build
```

## View Running Containers

```bash
docker ps
```

---

# DockerHub Repository

```plaintext
https://hub.docker.com/r/yourdockerhubusername/psusphere_docker
```

Replace `yourdockerhubusername` with your actual DockerHub username.

---



# Developers

* Clasara, Gethel Jayce M.
* Rivera, Sheena Marie C.
* BSIT3 B1

---

# Notes

* Make sure Docker Desktop is running before executing commands.
* Ensure that the required ports are available.
* Internet connection is needed when pulling images from DockerHub.

```
```
