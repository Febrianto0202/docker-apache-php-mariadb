# docker-apache-php-mariadb

Docker example with Apache, Mariadb, PhpMyAdmin and Php

- You can use MariaDB
- You can use MySql

Build Image
```
docker build -t apache:latest .
```

I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

Open phpmyadmin at [http://localhost:8000](http://localhost:8000)
Open web browser to look at a simple php example at [http://localhost:8003](http://localhost:8003)

Run mysql client:

- `docker exec -it mariadb mysql -u root -p` 

Enjoy !
