# Requirement 2: Infrastructure Integration (Deployment)

## 1. Install Docker and Docker Compose on your new Ubuntu Server

![Install Docker and Docker Compose](screenshot-1.png)

### Explanation

Docker and Docker Compose were installed on the Ubuntu Server to provide the environment needed to deploy and manage the cloud services using containers. After installation, the versions were checked to confirm that both Docker and Docker Compose were installed and working correctly.

**Docker version verification:**
```bash
docker --version
```

**Docker Compose version verification:**
```bash
docker compose version
```

These commands confirm that the Docker engine and Docker Compose are properly installed and ready to be used for deploying the project's containerized services.

---

## 2. Write a complete docker-compose.yml file

![Write a complete docker-compose.yml file](screenshot-2.png)

### Explanation

A complete `docker-compose.yml` file was created to define and configure the project's Docker services. The file contains the settings needed to run and connect the different containers, making it easier to deploy and manage the cloud application.

**First, go to the project directory:**
```bash
cd ~/enterprise-cloud
```

**Next, create or edit the Compose file:**
```bash
nano compose.yaml
```

The `compose.yaml` file is then used to define the required Docker containers, networks, volumes, and other configurations for the Enterprise Cloud Project.

---

## 3. The stack must include at least two linked containers

![The stack must include at least two linked containers](screenshot-3.png)

### Explanation

The Docker stack uses **two linked containers: WordPress and MySQL**. WordPress serves as the web application, while MySQL acts as the database that stores the website's data. The two containers are connected through the Docker network, allowing WordPress to communicate with the MySQL database.

After starting the Docker stack, the following command was used to verify that the containers are running:

```bash
sudo docker ps
```

The `sudo docker ps` command displays the currently running Docker containers, allowing us to confirm that both the **WordPress** and **MySQL** containers are active and running properly.

---

## 4. The database must utilize Persistent Volumes so that data survives a VM reboot

![Persistent Docker Volumes](screenshot-4.png)

### Explanation

The MySQL database was configured to use a **Persistent Volume** so that the stored database data will remain available even if the Ubuntu VM is restarted or rebooted. This helps prevent data loss and ensures that the WordPress website can continue using the existing database after the VM is turned back on.

**To verify the Docker volumes, use:**

```bash
sudo docker volume ls
```

The `sudo docker volume ls` command displays the Docker volumes available on the system. This confirms that a persistent volume is being used to store the database data separately from the MySQL container.
