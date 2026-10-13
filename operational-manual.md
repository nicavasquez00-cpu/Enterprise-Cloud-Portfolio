# Requirement 5: Technical Documentation

## Your GitHub repository must serve as the handover manual for the client's IT team.

### 1. Create a Comprehensive Operational Manual

![Operational Manual](operational-manual.png)

### Explanation

A comprehensive **Operational Manual** was created to serve as a handover guide for the client's IT team. The manual provides the necessary information for deploying, securing, operating, troubleshooting, and maintaining the Enterprise Cloud infrastructure.

The manual covers the configuration of the **Ubuntu Server, Docker, Docker Compose, WordPress, MySQL, persistent volumes, UFW firewall, database backups, and Cron Jobs**.

The complete operational instructions are available in:

```text
operational-manual.md
```

The manual provides step-by-step procedures that can help the IT team manage the system after the project has been handed over.

---

## 2. Include All Raw Code in the Repository

![Project Source Code](source-code-files.png)

### Explanation

The raw source and configuration files used in the Enterprise Cloud Project were included directly in the GitHub repository. This allows the client's IT team to review, modify, and reuse the project configuration when necessary.

The repository includes the following important files:

```text
docker-compose.yml
automation-script.sh
```

The `docker-compose.yml` file contains the configuration for the Docker services, including the WordPress application, MySQL database, networks, and persistent volumes.

The `automation-script.sh` file contains the Bash commands used to automate the database backup and operational tasks.

---

## 3. Final Reflection

![Final Reflection](final-reflection.png)

### Explanation

A **Final Reflection** was created to summarize the learning journey from **Mission 1 to Mission 10**. It discusses the development of the Enterprise Cloud infrastructure and the lessons learned from virtualization, containerization, networking, security, persistent storage, automation, disaster recovery, and technical documentation.

The complete reflection is available in:

```text
final-reflection.md
```

### Final Reflection

Throughout Missions 1 to 10, I learned how to build and manage an enterprise cloud environment step by step. I started with the basic infrastructure and Virtual Machine setup, then continued with Ubuntu Server configuration and networking.

As the project progressed, I learned how to use Docker and Docker Compose to deploy services such as WordPress and MySQL. I also learned the importance of persistent volumes because they allow database data to remain available even after restarting the Virtual Machine.

Security was another important part of the project. I configured the UFW firewall and learned how limiting access to only the necessary ports can help protect the server.

I also learned how automation can make server management easier. By creating a Bash backup script and scheduling it with Cron, regular database backups can be performed automatically without requiring manual execution.

Overall, Missions 1 to 10 helped me understand how different cloud technologies work together. I learned that a reliable cloud environment is not only about deploying applications but also about security, data persistence, automation, maintenance, and proper documentation. This project improved my practical skills and gave me a better understanding of how an IT team can manage and maintain a cloud infrastructure in a real-world environment.
