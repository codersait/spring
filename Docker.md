### Docker
- Postgres
  - `docker pull postgres:alpine`
  - `docker run --name postgres-0 -e POSTGRES_PASSWORD=password -d -p 5432:5432 postgres:alpine`
  - `docker ps`
  - `docker images`
  - `docker exec -it postgres-0 bash`
  - `psql -U postgres`
  - `psql -h localhost -p 5432 -U postgres`
  - `create extension if not exists "uuid-ossp";`
