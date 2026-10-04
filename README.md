# PHP Project - Producto 2 (UOC)

A booking and admin web app built for the PHP module at the Universitat Oberta de Catalunya (UOC). It includes:

- Docker setup with Apache, MySQL, and phpMyAdmin
- Framework-free MVC architecture (custom router, controllers, models, views)
- Structured to be migrated to Laravel in the next phase (Producto 3)

## Getting started

```bash
docker compose up -d --build
```

## Views

- Home: http://localhost:8083/?r=home/index
- Customer login: http://localhost:8083/?r=auth/login&type=particular
- Admin login: http://localhost:8083/?r=auth/login&type=admin
- Customer dashboard: http://localhost:8083/?r=dashboard/cliente
