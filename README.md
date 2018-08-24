postgresql-docker

# Introduction
This Docker Compose file is utilised to create an instance of Postgresql. As the data volume is mounted at `/var/lib/postgresql/data` data persistence is maintained between instances of this container. 

__NOTE__: If the `PGDATA` variable is changed, then the mount point of the Docker Volume will need to be changed in order to ensure persistence. 

`POSTGRES_USER`, `POSTGRES_PASSWORD` can be changed as required. 

`./data` within the current folder is used as an interface to copy and export data. 

This Docker Compose file has been setup to be used mainly for different projects and as such, the intention is to change the word `project` where required. 