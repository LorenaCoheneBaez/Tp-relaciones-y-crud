# CRUD de películas

## Objetivo:

Establecer la relación entre tablas usando una base de datos relacional.

Realizar un CRUD (create, read, update, delete) utilizando la base de datos, para las películas y los géneros.

****
### Pautas para las relaciones de la base de datos:

- Una película tiene un género.

- Un género tiene muchas películas.

- Una película tiene muchos actores.

- Un actor tiene muchas películas.

## Tecnologías usadas


<p align="left">
<!-- MYSQL -->
<a href="https://www.mysql.com/" alt="Express Js" ><img src= "https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" /></a>
<!-- EXPRESS -->
<a href="https://developer.mozilla.org/es/docs/Learn/Server-side/Express_Nodejs/Introduction" alt="Express Js" ><img src= "https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" /></a>
<!–– JAVASCRIPT ––>
<a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" data-bs-toggle="tooltip" title="JavaScript"> <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="javaScript"/> </a>
<!-- HTML -->
<a href="https://developer.mozilla.org/es/docs/Web/HTML" alt="HTML5" ><img src= "https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" /></a>
<!–– CSS ––>
<a href="https://www.w3schools.com/css/" target="_blank" data-bs-toggle="tooltip" title="CSS3"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="css3"/> </a>
<!–– BOOTSTRAP ––>
<a href="https://getbootstrap.com" target="_blank" data-bs-toggle="tooltip" title="Bootstrap"> <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="bootstrap"/></a>
  </p>

### Instalación de la base de datos relacional *movies-db.sql*:

- Debe tener instalado un gestor de base de datos, por ejemplo: MYSQL Workbench (https://www.mysql.com/products/workbench/) o Heidi db (https://www.heidisql.com/).

- Desde su gestor de base de datos, correr el script que se encuentra en:

   `Tp-relaciones-y-crud.git/src/database/script/movies-db.sql`

- Levantar el servidor para la base de datos desde su gestor de base de datos.

### ¿Cómo instalar el proyecto?

#### Desde la terminal:

- Clonar el proyecto:
````
git clone https://github.com/LorenaCoheneBaez/Tp-relaciones-y-crud.git
````
- Ingresar a la carpeta del proyecto:

````
 cd Tp-relaciones-y-crud.git
````

- Para instalar las dependencias correr: 

````
 npm install
````

### Levantar el servidor del proyecto: 

````
 npm test
````

### Rutas para el CRUD:

- Home http://localhost:3001/
- Listado de todas las películas http://localhost:3001/movies
- Detalle de película http://localhost:3001/movies/detail/:id
- Agregar película http://localhost:3001/movies/add
- Editar película http://localhost:3001/movies/edit/:id
- Eliminar película http://localhost:3001/movies/delete/:id
- Listado de géneros http://localhost:3001/genres
- Detalle de género  http://localhost:3001/genres/detail/:id