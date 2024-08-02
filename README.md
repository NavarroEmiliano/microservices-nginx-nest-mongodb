# Microservicio nginx, nestjs, mongodb

Descripción breve del proyecto.

## Requisitos

- Docker
- Docker Compose

## Instalación

1. **Clona el repositorio:**

    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    cd tu-repositorio
    ```

2. **Construye y levanta los servicios:**

    Asegúrate de tener Docker y Docker Compose instalados. Luego, ejecuta:

    ```bash
    docker-compose up --build
    ```

3. **Accede a los servicios:**

    - **Aplicación `store`:** Accede en [http://localhost:3004](http://localhost:3004)
    - **Aplicación `users`:** Accede en [http://localhost:3006](http://localhost:3006)
    - **Nginx (Proxy):** Accede en [http://localhost:80](http://localhost:80)

## Configuración

- **Nginx:** La configuración de Nginx se encuentra en `nginx/nginx.config`. Puedes ajustar la configuración según sea necesario.

- **MongoDB:** Los datos de MongoDB se guardan en `./mongo/db`. Puedes ajustar los volúmenes en el archivo `docker-compose.yml` si es necesario.

## Contribución

Instrucciones sobre cómo contribuir al proyecto.

## Licencia

Información sobre la licencia del proyecto.
