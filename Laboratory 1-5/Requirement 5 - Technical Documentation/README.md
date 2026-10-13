# Requirement 5: Technical Documentation

## Your GitHub repository must serve as the handover manual for the client's IT team.

## 1. Create a Comprehensive Operational Manual

The **Operational Manual** was created as a handover guide for the client's IT team. It explains how to deploy, secure, operate, troubleshoot, and maintain the Enterprise Cloud infrastructure.

The manual covers the Ubuntu Server, Docker, Docker Compose, WordPress, MySQL, persistent volumes, UFW firewall, database backups, and Cron Jobs.

**Operational Manual:**  
[Open operational-manual.md](../../operational-manual.md)

---

## 2. Include All Raw Code in the Repository

The raw configuration and source code used in the Enterprise Cloud Project were included directly in the GitHub repository. This allows the client's IT team to review and reuse the configurations when maintaining or redeploying the system.

### Docker Compose Configuration

The `docker-compose.yml` file contains the configuration for the Docker services, including the WordPress application, MySQL database, networks, and persistent volumes.

**Docker Compose File:**  
[Open docker-compose.yml](docker-compose.yml.png)

### Automation Script

The `automation-script.sh` file contains the Bash commands used to automate the database backup and operational tasks.

**Automation Script:**  
[Open automation-script.sh](../../automation-script.sh)

---

## 3. Final Reflection

The Final Reflection summarizes our group's learning journey from **Mission 1 to Mission 10**. It discusses how we developed the Enterprise Cloud environment and the lessons we learned about virtualization, containerization, networking, security, persistent storage, automation, disaster recovery, and technical documentation.

**Final Reflection:**  
[Open final-reflection.md](../../final-reflection.md)

---

## 4. Project Handover Files

The following files are provided as part of the project handover:

- [Operational Manual](../../operational-manual.md)
- [Docker Compose Configuration](../../docker-compose.yml)
- [Automation Script](../../automation-script.sh)
- [Final Reflection](../../final-reflection.md)
