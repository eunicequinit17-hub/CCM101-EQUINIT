
# Laboratory 09 - Cloud Automation Engineer

## Mission Overview

This mission demonstrates how Bash scripting and cron jobs can automate repetitive cloud administration tasks, especially application data backups.

## Objectives

- Understand Bash scripts and variables.
- Create and execute a backup script.
- Use chmod to assign execution permission.
- Compress application data into a timestamped archive.
- Schedule automated backups using cron.
- Document the process using Markdown.

## Commands Executed

```bash
mkdir app-data
echo "This is critical client data." > app-data/data.txt
cat app-data/data.txt
nano backup.sh
chmod +x backup.sh
./backup.sh
ls -l backups/
tar -tzf backups/*.tar.gz
crontab -l
env EDITOR=nano crontab -e
```

## Skills Learned

I learned how to write a Bash script, store values in variables, compress files, modify file permissions, and schedule recurring tasks using Linux cron.

