# Docker data store

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

## Database
- MySQL8.0.16

## Usage

`docker-compose up`

## Envoiroment

### MySQL

#### Default Environment


- user: `user`
- pass: `user!`
- root pass: `root`
- db: `myapp`
- port: `3306`

#### Custom Environment

```cp .env.example .env```

- Customizable Parameters
  - MYSQL_PORT
  - MYSQL_DATABASE
  - MYSQL_USER
  - MYSQL_PASSWORD
  - MYSQL_ROOT_PASSWORD
