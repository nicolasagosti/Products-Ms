# Product Microservice 

## Dev

1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en el `env.template`
4. Ejecutar migracion de prisma `npx prisma migrate dev`
5. Levantar contenedor de nats `docker run -d --name nats-main -p 4222:4222 -p 8222:8222 nats`
6. Ejecutar `npm run start:dev`


