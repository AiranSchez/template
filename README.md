# JavaScript Boilerplate

Para configurar la template debes entrar al package.json y cambiar lo siguiente:

- "name" : "template" -> "name" : "nombre de tu proyecto"
- "build": "... /nombre de tu proyecto/ ...",

La template incluye lo siguiente:

- 📙 Babel 7
- ✅ Jest 26
- 💅 Stylelint & ESLint & Sass

## npm scripts

- `start`: Arranca la aplicación en local
- `build`: Construye la applicación en la carpeta /build
- `deploy`: Despliega en GitHub Pages tu app
- `lint`: Ejecuta el linter para todo el proyecto
- `lint:fix`: Ejecuta el linter y arregla los ficheros del proyecto
- `test`: Ejecuta todos los tests
- `test:watch`: Ejecuta todos los test en modo observación
- `clean`: Quita las carpetas dist .cache build y el archivo package-lock.json
