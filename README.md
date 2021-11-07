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

4. Up

```shell
$ docker-compose up -d
```

## Resources

- [Docker images](https://hub.docker.com/r/redash/redash)
- [Environment variables](https://redash.io/help/open-source/admin-guide/env-vars-settings)
- [Upgrade from v8 to v10](https://github.com/getredash/redash/blob/v10.0.0/CHANGELOG.md#upgrading)
