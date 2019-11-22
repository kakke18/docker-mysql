docker-mysql
===
mysql for local development

## Description
This is an alternative to `mysql.server start`

In local development, you can easily start a MySQL server using Docker.

It also persists data to local storage.

## Usage
### Start
```
docker-compose up -d
```

### Update
```
docker-compose down
docker-compose up -d
```

### Stop
```
docker-compose stop
```
