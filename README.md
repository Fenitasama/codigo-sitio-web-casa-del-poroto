# codigo-sitio-web-casa-del-poroto

para correr este codigo bien necesitaremos: 
1) programas basicos 
-sql express instalado (es la instancia en la que corre la base de datos)
-node js y unas librerias que dire mas adelante 
ODBC Driver 17 for SQL Server que es lo que conecta el sql con node js 

2) abrir puerta tcp/ip de sql
   Presionar Windows + R poner compmgmt.msc
   en la izquierda buscar donde dice servicios y aplicaciones, ahi buscar la carpeta sql
   luego en donde dice sql server network... habilitar el tcp/ip
   en la pestaña de servicios buscar el sql express y reiniciar el servicio desde ahi

3) generar las tablas
    abrir sql los archivos ubicados en la carpeta database y abrir el primero y ejecutar
    abrir el segundo y ejecutar tambien
   asi creamos tablas necesarias para que guarde los datos en el sql
   (recordar que la instancia es en .\SQLEXPRESS)

5)  instalar librerias necesarias para ejecucion de servidor
   en la carpeta del sitio abrir el cmd y poner el comando
   npm install

6) probar si las conexiones estan bien hechas 
   lo mismo que el anterior, se abre cmd desde la carpeta del proyecto y se ejecuta el comando
   node test-db.js
   si dice conexion exitosa tamos flor fly

7) arrancamos servidor local
    siguiendo exactamnete lo anterior se habre cmd y se ejecuta el comando
    node src/server.js
   si dice servidor corriendo en.... esta listo

8) ejecutar sitio web
     para esto en el navegador hay que escribir
     http://localhost:3000
     ya que estamos corriendo de manera local

      y listo!!! :D ahora espero se entienda el por que nos demoramos tanto en empezar a presentar KJASHKJAS XD
      se le quiere profe victor gracias por la paciencia y lo aprendido <3
      atte: Fernando Rivas 

      
      
