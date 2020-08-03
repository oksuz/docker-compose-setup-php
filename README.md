# Docker-Compose Setup for Php - Mysql - Nginx

This setup provides php development environment on your computer using docker-compose.

put your php application in `site/` directory and then run `docker-compose up` command

go to `http://localhost:8080/phpinfo.php` through your browser and see php details.

### Notes for Nginx
`nginx-conf` folder contains nginx configurations for your virtual hosts

### Notes for MariaDB (Mysql)
* `db` folder is your mysql persistence directory that is mapping `/var/lib/mysql` folder in your docker instance
* `3306` port is exposed to host computer, please be careful when running this setup in public server.
* `1` is default root password, if you want to run public server please change it! *it is important* 



Customizations & custom configurations are welcome.

Happy Coding!
