# Backing up the Postgres database in Dropbox

1. git clone to /opt/

2. copy `.backup_config.dist` to `.backup_config`

3. Fill Config `.backup_config`

4. run `psql_backup` 

5. Or add to cron `ln -s /opt/psql_dropbox_backup/psql_backup /etc/cron.daily/psql_backup`