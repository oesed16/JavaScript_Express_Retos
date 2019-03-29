# Visitantes recurrentes

Crea una aplicación en Express que lleve la cuenta de cuántas veces visita cada persona la ruta `/`, guardando los datos en MongoDB.

- El nombre llega en el parámetro `name` (`/?name=Pedro`). Si no se envía, se usa **Anónimo**.
- Si el visitante ya existe, se aumenta en 1 su número de visitas. Si no, se crea con 1 visita.
- Después, muestra una tabla con el ID, el nombre y el número de visitas de todos los visitantes.

Usa Mongoose y una vista `ejs` para la tabla.

## Cómo ejecutarlo

Necesitas MongoDB corriendo en `localhost:27017`, o una URL de conexión en la variable `MONGODB_URL`.

```bash
npm install
node app.js
```

Abre http://localhost:3000/?name=Pedro
