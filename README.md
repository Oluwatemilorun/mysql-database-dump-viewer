# MySQL Database Dump Viewer

This helps to open and view a MySQL database dump on a web interface using PHPMYADMIN

## How to Use

- Get the db dump and copy it into the `./dump` folder. Rename it to `db.sql`
   ```bash
   mv /path/to/db/dump.sql ./dump/db.sql
   ```
- Update the `.env` file with the credentials of your database and dump
- Start up the service with `docker-compose up --build`
- Open http://localhost:8090 to reveal the phpMyAdmin dashboard login portal
- Login using the value of `MYSQL_USER` as the username and `MYSQL_PASSWORD` as the password

## Requirements

- Docker
