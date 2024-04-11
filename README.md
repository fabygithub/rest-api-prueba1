# rest-api-prueba1

cmd

npm init -y   - crear node
npm install express body-parser - crear los servicios
node app.js - ejecutar en localhost

postman

http://localhost:3000/items/1 - borrar un usuario
http://localhost:3000/items - get -  ver los usuarios
http://localhost:3000/items - post - { "id": 3, "name": "Item 3" } - agregar un usuario
http://localhost:3000/items/1 - actualizar -   {"id": 1, "name": "juan"} - actualizar usuario


front end

npm install pug -  agregar html
app.set('view engine', 'pug'); - agregar app.set
mkdir views - crear carpeta 
nano views/default.pug - crear el archivo pug
nano views/home.pug - pagina de inicio

