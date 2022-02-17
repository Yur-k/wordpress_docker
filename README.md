# WordPress With Docker Compose

### To run WordPress is [recommended](https://wordpress.org/about/requirements/) your host have supports: 
* PHP 
* MySQL 
* Apache or Nginx as the most robust and featureful server for running WordPress 

These files will setup Wordpress, MySQL, PHP and nginx on localhost with a single command:
```
$ docker-compose up -d

# To Tear Down
$ docker-compose down --volumes
```
## Files
`docker-compose.yml` - main file  
`.env` - contain data for MySQL  
`nginx` - server configuration file  

## Pre-requirements
* [Install docker](https://docs.docker.com/engine/install/)
* [Install docker-compose](https://docs.docker.com/compose/install/)

## Useful links
* [Detailed guide how to install WordPress with Docker Compose](https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose) 
* [nginx configuration for WordPress and PHP](NGINX )

### Docker Images:
* [WordPres + PHP](https://hub.docker.com/_/wordpress)
* [MySQL](https://hub.docker.com/_/mysql)
* [nginx](https://hub.docker.com/_/nginx)

