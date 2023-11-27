# Aplicación de Monitoreo - MongoDB y PostgreSQL

Se aplica la integración de base de datos con MongoDB y PostgreSQL en nuestra aplicación de `NOC`, los temas que se ven son:

1. Uso de `Mongoose`, `Prisma` y `TypeORM`.
2. Migraciones de prisma
3. Insertar en base de datos
4. Mapeo de `data` a Entidades
5. Creación de `datasources`.

### Para iniciar proyecto

1. Instalar las dependencias. 
```
npm install
```
2. Renombrar el archiv `.env.template` a `.env` y definir las variables de entorno.
3. Levantar las bases de datos con el comando: 
```
docker compose up -d
```
4. Ejecutar la aplicación. 
```
npm run dev
```



