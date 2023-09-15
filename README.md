# Argentina Programa 4.0




<h1 align="center"> Proyecto Integrador FORO</h1>

Repositorio desarrollado como examen integrador de Programa 4.0 y Epica Sapem.

DESCARGAR LOS SIGUIENTES LINK.

[Express Nodejs](https://miro.medium.com/v2/resize:fit:1400/1*f7ztMaMM0etsFHpEfkdiwA.png) 



[EJS](https://cdn.hashnode.com/res/hashnode/image/upload/v1669904581074/eiOU4pInF.png) 



[XAMPP](https://www.sysadminsdecuba.com/wp-content/uploads/2015/08/xampp-logo.jpg)

PRIMER LUGAR           SEGUNDO LUGAR    TERCER LUGAR
| Express Node.js      | EJS            | XAMPP |

>>>>>>>>>>>>>>>>>>>>>>>>>>>>> Guía de Instalación y Ejecución

GUIA COMO EJECUTAR EL PROYECTO EN SU PC
1. **Descarga el ZIP DEL REPOSITORIO.**

2. **Instalar las dependencias :**
  EN TERMINAL (npm i nodeapp.js)
```
   npm i
```

3. **CONFIGURAR la base de datos MySQL:** 

   REALIZAR UNA base de datos llamada `forodb` 

4. **COLOCAR datos del archivo .example.env y cambie el nombre a .env: sino lo cambia no funciona**
!!!!
   PORT=6969
   HOST_DB=localhost
   DIALECT_DB=mysql
   USER_DB=root
   PASS_DB=''
   NAME_DB=forodb
!!!!
7. **creacion tabla base de datos para los posteos agregue NOMBRE: "publicaciones" GUIA DE datos para las columnas:**
   
 !!!!
   publicaciones / utf8_general_ci
   id = int
   titulo = varchar 255
   detalle = text
   url_imagen = varchar 255
   fecha_publicacion = date   
!!!!
6. **Ejecute node app.js y acceda de manera predeterminada a la aplicación en su navegador web en el PORT=6969 .env :**
[http://localhost:6969](http://localhost:6969).