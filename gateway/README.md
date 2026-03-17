## API Gateway

This service is the entry point for all requests in the microservices architecture.
It handles authentication and routing.

---

## Authentication

Authentication is managed by **Keycloak**.  
To access the Keycloak admin console, open:
```
http://localhost:8080
```

---

## Running locally

Start the required services with Docker Compose:
```bash
docker-compose up -d
```

This will start Keycloak and all other dependencies.