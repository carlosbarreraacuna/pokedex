1.	Ejecutamos el comando npm install 
 
![alt text](image.png)

2.	Ejecutamos el comando npm run build y esto nos generara una carpeta dist en nuestro proyecto
 
![alt text](image-1.png)

Nos dirigimos al portal de azure

Creamos un grupo de recurso llamado app web service

 ![alt text](image-2.png)

 ![alt text](image-3.png)


Nos dirigimos a herramientas avanzadas

 ![alt text](image-4.png)

Nos dirigimos a Debug console y le damos em cmd

 ![alt text](image-5.png)

Nos dirigimos a la ruta de site/ wroot y añadimos el contenido de la carpeta dist


![alt text](image-6.png)

 
Y accedemos al link que nos genera el portal de azure y este es el resultado 

 ![alt text](image-7.png)


Para gestionar los problemas de seguridad de la aplicación y que también esta cuente con una seguridad hacemos los pasos siguientes: 

 Creamos un archivo web.config con las configuraciones 

![alt text](image-8.png)
 

Accedemos al link https://securityheaders.com/ para verificar la seguridad que tiene nuestro sitio y este es el resultado final

  ![alt text](image-9.png)
