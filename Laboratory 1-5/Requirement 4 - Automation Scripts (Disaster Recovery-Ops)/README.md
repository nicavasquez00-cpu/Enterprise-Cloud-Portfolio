# Requirement 4: Automation Scripts (Disaster Recovery/Ops)

## Your server must manage itself autonomously.

### Explanation

A custom **Bash shell script** was created to perform a critical operational task for the Enterprise Cloud Project. The script is designed to automate the **database backup process**, helping protect important data and support disaster recovery.

The script was saved as a `.sh` file and was made executable so that it can be run automatically by the server.

**To make the script executable, use:**

```bash
chmod +x automation-script.sh
```

**To run the script manually for testing, use:**

```bash
./automation-script.sh
```

The `chmod +x` command gives the Bash script permission to execute, while `./automation-script.sh` runs the script manually to verify that the backup process works correctly.

---

## Write a custom Bash shell script (.sh) that performs a critical operational task

### Explanation

The Bash script performs a **database backup** and saves the backup file in a designated backup directory. This provides a copy of the database that can be used for recovery if the original data is lost or damaged.

**To go to the project directory, use:**

```bash
cd ~/enterprise-cloud
```

**To check the backup files, use:**

```bash
ls -lh ~/enterprise-cloud/backups
```

The command displays the available backup files and helps verify that the database backup was successfully created.

---

## The script must be executable.

### Explanation

The backup script was given executable permission so that it can be executed directly by the Ubuntu Server. This is necessary before the script can be scheduled through Cron.

**Command:**

```bash
chmod +x automation-script.sh
```

**To verify that the script is executable, use:**

```bash
ls -l automation-script.sh
```

The output should show an executable permission such as `-rwxr-xr-x`.

---

## You must configure a Cron Job to schedule this script to run automatically at a specific time.

### Explanation

A **Cron Job** was configured to automatically execute the backup script at a scheduled time. This allows the server to perform regular database backups without requiring manual execution.

**To open the Cron Job configuration, use:**

```bash
crontab -e
```

**Example scheduled task:**

```bash
0 0 * * * /home/YOUR_USERNAME/enterprise-cloud/automation-script.sh
```

This schedule runs the backup script **every day at 12:00 AM**.

**To verify the scheduled Cron Job, use:**

```bash
crontab -l
```

The `crontab -l` command displays the configured scheduled tasks and confirms that the backup script is set to run automatically.
