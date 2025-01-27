# Wordpress and Docker boilerplate

This is a starter kit for wordpress theme and plugin development environment by docker .

## Used tools

1. `Docker` for containerization
2. `Wordpress` web content management system
3. `MariaDB` database
4. `PHPMyAdmin` database administration

## Usage

Make sure docker is installed on your machine and run this line:

```
docker-compose up -d
```

After that you can easily access your Wordpress website on your [localhost:8000](http://localhost:8000) and PHPMyAdmin on [localhost:8001](http://localhost:8001)

For using as a development tool and changing files with your user use:

```
chmod 777 -R wordpress
```
