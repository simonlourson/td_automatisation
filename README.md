# Redhat

## Exercice 1: Write a backup script
Backups is a common tasks that needs to be automated. Write a shell script `backup.sh` that will :
1. [Compress](https://www.redhat.com/en/blog/taming-tar-command) a directory you want to backup in a single file : `backup.tar.gz`
   - (if you want to backup the `web_viz` directory, you can try to exclude the `__pycache__` directory from the backup)
2. [Add a timestamp](https://stackoverflow.com/questions/8228047/adding-timestamp-to-a-filename-with-mv-in-bash) to the name of your backup : `backup_202412060945.tar.gz`
3. Move the backup file to another directory

## Exercice 2: Make your backup script run every 5 minutes
Most linux system use [crontab](https://www.redhat.com/en/blog/linux-cron-command).

# Windows

## Exercice 1: Write a backup script
With windows, you can use either batch (`*.bat` files) or powershell (`*.ps1` files)

## Exercice2 : Make your backup script run every 5 minutes
With Windows, you can use the Task Scheduler
