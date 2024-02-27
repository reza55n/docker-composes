# docker-composes
`cd` to the desired directory and run:

`docker-compose up --build`


You can change the public port number for each `docker-compose` from inside the `docker-compose.yml` - the first number from `ports` key. For example, in `php-nginx-postgres`, change the related value from `3793:3793` to `80:3793`.



## php-apache-postgres
Public port number: 8132


### Test
Two containers (PHP and Postgres) were run successfully and `PHP` files were served and `.htaccess` operated.

Also below command successfully gave an empty response from inside the PHP container:

`curl "postgres-db:5432" -v`



## php-nginx-postgres
Public port number: 3793


### Test
Three containers (PHP, Nginx and Postgres) were run successfully and `PHP` files were served.

