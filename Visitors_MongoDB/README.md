# Visitantes

Crea una aplicación en Express que guarde en MongoDB cada visita a la ruta `/`.

- Cada visitante se guarda con la fecha de la visita y el nombre que llega en el parámetro `name` (`/?name=Pedro`).
- Si no se envía el nombre, se guarda como **Anónimo**.
- Después de guardar, responde: **El visitante fue almacenado con éxito**

Usa Mongoose para definir el esquema y el modelo.

## Cómo ejecutarlo

Necesitas MongoDB corriendo en `localhost:27017`, o una URL de conexión en la variable `MONGODB_URL`.

```bash
npm install
node app.js
```

Abre http://localhost:3000/?name=Pedro
