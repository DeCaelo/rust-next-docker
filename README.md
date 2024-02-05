- docker compose up -d
- docker ps -a
- docker exec -it db psql -U postgres
- \l
- \dt
- docker compose build
- docker compose up -d rustapp

```bash
  curl http://localhost:8080/api/users
```

```bash
 curl -H "Content-Type: application/json" -X POST -d '{"name": "john doe", "email": "john.doe@email.com"}' http://localhost:8080/api/users
```

- https://blog.logrocket.com/create-backend-api-with-rust-postgres/
- https://medium.com/@govinda.attal/containerize-rust-service-and-pattern-to-support-unit-tests-a491d28118c0
