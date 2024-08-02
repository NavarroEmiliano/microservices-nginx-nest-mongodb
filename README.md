# Microservices with NestJS, MongoDB, and Nginx

A project that demonstrates a microservices architecture using NestJS, MongoDB, and Nginx.

## Requirements

- Docker
- Docker Compose

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/NavarroEmiliano/microservices-nginx-nest-mongodb.git
    cd microservices-nginx-nest-mongodb
    ```

2. **Build and start the services:**

    Make sure you have Docker and Docker Compose installed. Then, run:

    ```bash
    docker-compose up --build
    ```

3. **Access the services:**

    - **Store Application:** Access at [http://localhost:3004](http://localhost:3004)
    - **Users Application:** Access at [http://localhost:3006](http://localhost:3006)
    - **Nginx (Proxy):** Access at [http://localhost:80](http://localhost:80)

## Configuration

- **Nginx:** The Nginx configuration can be found in `nginx/nginx.config`. You can adjust the configuration as needed.

- **MongoDB:** MongoDB data is stored in `./mongo/db`. You can adjust the volumes in the `docker-compose.yml` file if needed.

