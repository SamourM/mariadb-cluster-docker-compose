# mariadb-cluster-docker-compose

run "docker-compose up -d" and it will fire up the 3 containers like magic.

You can attach host directories by adding below to docker-compose file.

volumes:
- /data/docker/MariaDB1:/data
