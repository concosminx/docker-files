# Docker Backup 

https://restic.net/

# Restore
- check the backups with `sudo docker exec restic snapshots -H host_name_from_compose_file` and find the id
- get the id
- restore with `sudo docker exec restic restic restore --target /tmp-for-restore id`
- shut down the containers, copy the data from `tmp-for-restore` and start the containers
