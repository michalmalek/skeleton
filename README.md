## About

Skeleton is small docker driven starting point to create applications with PHP-7.2, NginX and MySQL.

Provides basic infrastructure to create and develop any web application or service.

## Installation

- Install [Docker](https://www.docker.com/products/docker-desktop) on your machine
- Learn [Docker Basics](https://docs.docker.com/get-started/)
- Download repository
- Configure your development envirnoment (read [Configuration](#configuration) section)
- Start work on your application under application directory

## Documentation

#### Configuration

Please read comments in **docker-compose.yml** and **.env**

#### Directory Structure

```
application/        php application code
  public/           data exposed to public
data/               docker containers volumes
  mysql/            mysql volume
docker/             docker data
```

## Project background

This project was started as docker tutorial and I thought that it can be useful later.

I plan to maintain this for at least while but any help will be appreciated.