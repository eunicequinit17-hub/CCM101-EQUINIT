
# Backup Script Guide

## 1. Purpose

The backup script automatically compresses the application data directory into a timestamped `.tar.gz` archive.

## 2. Full Bash Script

```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

cd /root || exit 1

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

mkdir -p "$BACKUP_DIR"
tar -czf "$BACKUP_DIR/backup_$TIMESTAMP.tar.gz" "$SOURCE_DIR"

echo "Backup completed successfully at $TIMESTAMP!"
```

## 3. File Permissions

The command `chmod +x backup.sh` adds executable permission to the script, allowing it to run as a program.

## 4. Cron Schedule

```cron
0 2 * * * /root/backup.sh
```

### Cron Field Breakdown

| Field | Value | Meaning |
|---|---|---|
| Minute | 0 | At minute zero |
| Hour | 2 | At 2 AM |
| Day of Month | * | Every day of the month |
| Month | * | Every month |
| Day of Week | * | Every day of the week |

The cron job schedules the backup script to run every day at 2:00 AM, using the system's local time.

## 5. Verification

The backup was tested by executing the script and listing the generated archive in the backups directory. The cron schedule was verified using `crontab -l`.

