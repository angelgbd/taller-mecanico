# Taller Mecánico

Proyecto de práctica con Prisma ORM 7 y MySQL. El esquema modela clientes, vehículos, órdenes de servicio y refacciones.

## Preparar el entorno

1. Instala dependencias con `npm ci`.
2. Copia `.env.example` a `.env` y coloca ahí tus credenciales locales de MySQL.
3. Crea la base de datos `taller_mecanico` si todavía no existe.
4. Genera Prisma Client con `npm run db:generate`.
5. Aplica las migraciones de desarrollo con `npm run db:migrate`.

El archivo `.env` contiene datos locales y está excluido del repositorio. Las migraciones versionadas están en `prisma/migrations/`.

## Comandos

- `npm run db:generate`: genera Prisma Client en `generated/prisma/`.
- `npm run db:migrate`: crea y aplica migraciones en desarrollo.
- `npm run db:studio`: abre Prisma Studio.
