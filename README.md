# docker-compose-redash

1. Git clone

```shell
$ git clone https://github.com/yyoshiki41/docker-compose-redash
```

2. Pull docker images

```shell
$ docker-compose pull
```

3. Create database tables

```shell
$ docker-compose run --rm server create_db
```
