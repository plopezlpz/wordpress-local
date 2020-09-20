# Wordpress digital ocean
Instructions from this link: https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose


## Quick start

Create a `.env` file with the following data:
```
MYSQL_ROOT_PASSWORD=
MYSQL_USER=
MYSQL_PASSWORD=
```

Run the docker-compose command:
```
docker-compose up -d --force-recreate
```