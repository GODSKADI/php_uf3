1. Crear una BBDD con el nombre "login", con el comando:

  <br />1.1 Primero entramos al mysql con nuestro usuario, con el comando:
       <br />$ mysql -u "nombre" -p 
       <br />Enter password: "contraseña"
 <br />
  __1.2 Segundo creamos la BBDD con el comando:
      __mysql> CREATE  database world
<br />

2. Importar la BBDD login.sql con el comando:
  __$ mysql -u "user_name" -p login < login.sql
  __Enter password: "user_password"
    
    
3. Remplazar la linea $conn = mysqli_connect('localhost','skadi','P@ssw0rd'); de los archivos login.php y login.php por:
<br />
__$conn = mysqli_connect('localhost',"user_name", "user_password");


Informacion sobre los Usuarios de la BBDD:

ID: 1
usuario: skadi
password: 1234

ID: 2
usuario: bob
password: 4321

ID: 1
usuario: trudi
password: 1423

ID: 2
usuario: alice
password: hola
