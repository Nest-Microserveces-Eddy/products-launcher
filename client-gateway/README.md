## Cliente Gateway

## Dev

1. Clonar el Repositorio
2. Instalar Dependencias
3. Crear un archivo `.env` basado en el `env.template`
4. Levantar el Servidor de NATS
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
5. Tener levantados los microservicios que se van a consumir
6. Levantar proyecto con `npm run start:dev`



## NATS

docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats