# Autenticación

Agrega autenticación al formulario de registro, guardando los usuarios en MongoDB.

- `/register`: formulario para crear un usuario con nombre, email y contraseña. La contraseña se guarda cifrada con `bcrypt`.
- `/login`: formulario para ingresar con email y contraseña. Si los datos son correctos, se guarda el usuario en la sesión y se redirige a `/`. Si no, se muestra un error.
- `/`: solo se puede ver si el usuario ingresó; muestra la lista de usuarios registrados. Si no ha ingresado, se redirige a `/login`.
- `/logout`: cierra la sesión.

Usa Mongoose, vistas `ejs` y sesiones con cookies.

## Cómo ejecutarlo

Necesitas MongoDB corriendo en `localhost:27017`, o una URL de conexión en la variable `MONGODB_URL`.

```bash
npm install
node app.js
```

Abre http://localhost:3000
