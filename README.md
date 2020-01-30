## AppXen LAMP Stack

AppXen Open Source LEMP Stack provides a complete, containerized, fully-integrated and ready to run PHP, MySQL and NGINX development environment. In addition, it bundles phpMyAdmin, SQLite, ImageMagick, FastCGI, Memcache, GD, CURL, PEAR, PECL and other components including Mail Catcher for debugging mail and smtp enabled applications.

https://appxen.com/app/lamp-stack

* PHP
* Apache
* MySQL
* phpMyAdmin
* Redis

# Quickstart

Clone this repository on your local computer and checkout the appropriate branch e.g. 7.4.x. 
Run the `docker-compose up -d`.

```shell
git clone https://github.com/aws-appxen/docker-compose-lamp.git
cd docker-compose-lamp/
git fetch --all
git checkout 7.4.x
cp env.dist .env
docker-compose up -d
```

Your LAMP stack is now ready!! You can access it via `http://localhost`.

Run it with one-click on EC2 - https://appxen.com/app/lamp-stack
