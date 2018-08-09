A basic set-up of PostgreSQL High Available using Patroni with Zookeeper and HAProxy.

## How-to
Simply start using docker-compose. Initially the zookeeper container will start and than patroni will get
the cluster working.

## Reference

The set-up is based on the patroni documentation which can be found on [github](https://github.com/zalando/patroni) and the
docker image provided by PostgreSQL.

HAproxy uses the default haproxy docker image but it is still build to have the config file
inside the image for convenience. You can see the stats on http://localhost:7000

Default PostgreSQL port exposed on `localhost:5432`. (login: _postgres/grespost_)
