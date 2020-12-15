# nginx reverse proxy

This is a project template for a reverse proxy to an otherwise network-isolated
backend service using Docker Compose.

## Usage

* Copy .env.example to .env and define the variables. NGINX_PORT and BACKEND_PORT may be the same or different.
* docker-compose up
* Access http://localhost/yes.svg
