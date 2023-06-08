# Conexion-MongoDB

Crear base de datos

1- Crear cuenta en https://www.mongodb.com/

2- Configura y crear Base de datos (Guardar Contraseña de acceso)

3- Seleccionar el boton connect y despues drivers 

4- Copiar Codigo para enlazar con mongodb (Se utiliza mas adelante)


--Conexion a MongoDb--

1- Abrimos Visual Studio Code

2- Abrimos la carpeta backend_mongoDB

3- Abrimos la Terminal y nos posicionamos en la carpeta

4- Ejecutamos el comando npm init


  --Instalamos dependencias--
  

5- Ejecutamos npm install dotenv

6- Ejecutamos npm install express

7- Ejecutamos npm install mongoose

8- Ejecutamos npm install nodemon

9- Creamos un archivo .env , dentro declaramos MONGO_URI_TEST="Aqui pegamos el codigo de enlace"

10- Dentro del codigo de enlace Remplazamos <password>  con la contraseña creada para acceder a esa base de datos

11- En el archivo package.json creamos dentro de scripts ,"start": "nodemon index.js"

12- Ejecutamos el comando npm run start y el servidor empieza a trabajar 

