## To run redis on your machine

Clone the current repositoy to your machine

```bash
$ git clone 'https://github.com/moeldeeb1998/redis-docker.git'
```

Change to the directory of this project

```bash
$ cd /path/to/project
```

To start redis

```bash
$ PASS=<YOUR_REDIS_PASSWORD> docker-compose up -d
```

To open redis-cli

```bash
docker exec -it redis redis-cli -a <YOUR_REDIS_PASSWORD>
```

To stop redis

```bash
docker-compose down
```
