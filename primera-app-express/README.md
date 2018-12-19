# Primera App Express

Primera aplicación con [Express](https://expressjs.com/). Sobre el mismo `app.js` se resolvieron varios retos pequeños, uno después del otro (cada uno quedó en su propio commit):

1. **Hola Mundo:** en la ruta `/` responde **Hola Mundo** dentro de un `<h1>`.
2. **Texto fijo:** en la ruta `/` responde exactamente con el texto `HcUy6Re2LLBRtj`.
3. **Hola desconocido:** en la ruta `/` saluda con el parámetro `nombre` (`/?nombre=Pedro` → **Hola Pedro!**). Si no se envía, muestra **Hola desconocido!**
4. **Salúdame 2:** la ruta `/makers/:nombre` saluda con el nombre de la URL, con la primera letra en mayúscula (`/makers/pedro` → **Hola Pedro!**).
5. **Pares e impares:** en la ruta `/` muestra los números del 1 al 50 indicando si cada uno es par o impar (`1 Soy Impar!`, `2 Soy Par!`, ...).
6. **Encabezados:** en la ruta `/` muestra el *user agent* del navegador, leyendo el encabezado `User-Agent` de la petición.

## Cómo ejecutarlo

```bash
npm install
node app.js
```

Abre http://localhost:3000
