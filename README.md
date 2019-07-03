# happs

This docker-compose file create 2 linked containers: db and php

## db container

It's the first container to be created, with the following ENV variables:

`DB_USERNAME=happs`

`DB_PASSWORD=happs`

`DB_DATABASE=happs`


## php container

It's basically php:7.1 that install composer during the run
