# Retos Express

Soluciones a una serie de retos para practicar [Node.js](https://nodejs.org/es), [Express](https://expressjs.com/) y [MongoDB](https://www.mongodb.com/): rutas, parámetros, formularios, vistas (`pug` y `ejs`), encabezados HTTP, bases de datos con Mongoose y autenticación con sesiones.

Cada carpeta contiene un reto con su descripción (`README.md`) y su solución (`app.js`).

## Instalación

Necesitas tener [Node.js](https://nodejs.org/es) instalado. Los retos que usan base de datos necesitan además MongoDB corriendo en `localhost:27017`, o una URL de conexión en la variable `MONGODB_URL`.

Para ejecutar un reto, entra a su carpeta, instala las dependencias y corre la aplicación:

```bash
cd primera-app-express
npm install
node app.js
```

Abre http://localhost:3000 en el navegador.

## Retos

| Reto | Descripción |
|---|---|
| [Primera App Express](primera-app-express/README.md) | Primeros retos con Express: Hola Mundo, parámetros, rutas, pares e impares y encabezados |
| [Salúdame 3](saludame_3_express/README.md) | Formulario que envía un nombre y saluda |
| [Visitantes](Visitors_MongoDB/README.md) | Guardar cada visita en MongoDB |
| [Visitantes recurrentes](VisitantesRecurrentes/README.md) | Contar las visitas de cada persona |
| [Formulario de registro](form-register/README.md) | Registrar usuarios en MongoDB |
| [Autenticación](autenticacion-express-mongo/README.md) | Registro, login y sesiones |
