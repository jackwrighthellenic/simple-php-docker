# Simple PHP Docker

This repository is a simple Docker Compose config designed to get a test PHP environment up in minutes including PHPMyAdmin.

## Installation

- Install Git and Docker on your machine.
- Run `git clone https://github.com/jackwrighthellenic/simple-php-docker`
- `cd` to the project directory that has just been cloned.
- Run `docker-compose up`
- Done!

## Notes

The site should be immediately accessible at `localhost` via port `80`.

You can access PHPMyAdmin via `localhost:8080`.

Database credentials are specified and can be modified in `docker-compose.yml`.

Direct database access is not done via `localhost`. Please use `db` as the hostname in your test PHP app instead.
