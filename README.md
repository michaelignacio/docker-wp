# Getting Started

`docker-wp` is a docker-compose configuration that pulls the latest Wordpress image to use with Docker. Pull this repo to your project folder, and:

1. Rename `.env.example` to `.env` and update `COMPOSE_PROJECT_NAME` to the project name.
2. Run `docker-compose up -d` to instantiate Wordpress.
3. Add the necessary line to your `hosts` file, e.g:
```
127.0.0.1 local.wordpress
```
where `local.wordpress` is the custom local domain name.

Alternatively, you can also use another port other than 80 to use a localhost port as the local domain (i.e. `localhost:8000`).