### raspisync

personal script for sending incremental backups to a remote server using rsync.

useful links:

- https://raspberrypi.stackexchange.com/a/5492
- https://raspberrypi.stackexchange.com/a/28087

example command: `./raspisync root@my.backup.server.com /opt/backups/raspberrypi`

for automated runs, a cronjob like this should be enough:

`@daily /usr/bin/raspisync root@my.backup.server.com /opt/backups/raspberrypi`