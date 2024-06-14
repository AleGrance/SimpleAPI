# Simple Nodejs API

Simple Nodejs fue creado usando NodeJS, Express, Babel, Sequelize y PostgreSQL

## Installation I

Clonar el repositorio y ejecutar npm install en la carpeta raiz del proyecto

```bash
npm i
```
## Installation II

-Instalar PostgreSQL
-Crear la base de datos a utilizar

## Config I

Crear el archivo .ENV en la raiz del proyecto y agregar los siguientes datos

DB_NAME=nombre_de_la_base
USER_NAME=user_de_la_base
USER_PWD=password_de_la_base
API_KEY=abc123

## Usage I

Incluye nodemon para el entorno de desarrollo. Ejecutar npm run dev mientras se esta desarrollando

```bash
npm run dev
```

### Header HTTP

Agregar el apikey en el header de cada solicitud. El apikey puede ser modificado si así lo desea

```bash
apikey: abc123
```

### Metodos HTTP

Obtener roles
```bash
http://localhost:3000/api/roles
```

Obtener users
```bash
http://localhost:3000/users
```

## Usage II

Para ejecutar en produccion necesitas correr el comando npm run build para transpilar el codigo y npm start para ejecutar el proyecto en produccion

```bash
npm run build
npm start
```

## Author
Alejandro Grance
