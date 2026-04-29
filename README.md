# StreamLine API 🎬

![Java](https://img.shields.io/badge/Java-17-blue)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-green)

API REST para gestionar suscripciones de la plataforma de streaming StreamLine.

## ¿Qué hace?
- Listar todas las suscripciones
- Buscar por ID
- Filtrar suscripciones activas
- Buscar por categoría
- Crear, actualizar y eliminar suscripciones

## Tecnologías
- Java 17
- Spring Boot
- Persistencia en memoria (ArrayList)

## Endpoints
| Método | Endpoint | Descripción |
|--------|----------|-------------|
| GET | /api/subscriptions | Lista todas |
| GET | /api/subscriptions/{id} | Busca por ID |
| GET | /api/subscriptions/active | Solo activas |
| GET | /api/subscriptions/search?cat= | Busca por categoría |
| POST | /api/subscriptions | Crea nueva |
| PUT | /api/subscriptions/{id} | Actualiza |
| PATCH | /api/subscriptions/{id}/status | Cambia estado |
| DELETE | /api/subscriptions/{id} | Elimina |
