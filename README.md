# WordPress With Docker Compose


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#Usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This progect can help setup Wordpress, MySQL and PHP on your localhost


### Built With
* [Docker](docker.com)
* [nginx](nginx.org)

Docker Images:
* [WordPres + PHP](https://hub.docker.com/_/wordpress)
* [MySQL](https://hub.docker.com/_/mysql)
* [nginx](https://hub.docker.com/_/nginx)

<!-- GETTING STARTED -->
## Getting Started

To run WordPress is [recommended](https://wordpress.org/about/requirements/) your host have supports: 
* PHP 
* MySQL 
* Apache or Nginx as the most robust and featureful server for running WordPress 

### Prerequisites

You need to install Docker and Docker-compose. You can use script `docker-install.sh`
  ```sh
./docker-install.sh
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Yur-k/wordpress_docker
   ```
2. Deploy WordPress with Docker
   ```sh
   docker-compose up -d
   ```
3. To tear down
   ```sh
   docker-compose down
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Open browser and enter
```
localhost
```
Enjoy

## Useful links
* [Detailed guide how to install WordPress with Docker Compose](https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose) 
* [nginx configuration for WordPress and PHP](NGINX)

<!-- CONTACT -->
## Contact

Yurii - yura.ryzhuk@gmail.com  
LinkedIn: [Yurii Ryzhuk](https://www.linkedin.com/in/yurii-ryzhuk-b13580206/)
Project Link: [https://github.com/Yur-k/wordpress_docker](https://github.com/Yur-k/wordpress_docker)  

<p align="right">(<a href="#top">back to top</a>)</p>


