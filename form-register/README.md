# Formulario de registro

Crea una aplicación en Express con un formulario de registro que guarde los usuarios en MongoDB.

- La ruta `/` muestra una tabla con el nombre y el email de los usuarios registrados, y un enlace para registrarse.
- La ruta `/register` muestra un formulario con nombre, email y contraseña.
- Al enviar el formulario (`POST /register`) se crea el usuario y se redirige a `/`.

Usa Mongoose y vistas `ejs`.

## Cómo ejecutarlo

Necesitas MongoDB corriendo en `localhost:27017`, o una URL de conexión en la variable `MONGODB_URL`.

```bash
npm install
node app.js
```

Abre http://localhost:3000
