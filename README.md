# Práctica 3.9: Despliegue web con bases de datos en AWS. Nivel básico.

## RDS

## EC2
Creamos una ec2 limpia para evitar errores y posibles problemas en otros trabajos posteriores. Le pondremos nombre, seleccionaremos el sistema operativo, que en nuestro caso sera un ubuntu 18.04, dejaremos que cree un grupo de seguridad nuevo y le daremos a lanzar instancia, sino tenemos errores nos llevara directamente a la instancia que se estara iniciando. 

## S3
En primer lugar hemos creado un nuevo nuevo bucket con el nombre practica3.BelenYLaura. Dejamos la ubicacion que nos viene por defecto. No tocamos nada hasta llegar a la parte BLoqueo todo el acceso público y aceptamos el problema que sale para poder crearlo 
- ![Buckets creado](trabajo%20bd.png)
Una vez creamo nos metemos dentro para poder añadir las carpetas que luego mostraremos en la EC2.
Para ello nos descargamos los documentos que nos a proporcionado la profesora, como es un archivo .zip lo descomprimimos y subimos los archivos que estan dentro de la carpeta. Este paso es importante ya que si no subimos los archivos como se debe nos puede dar futuros errores.
Le damos a cargar y si no nos da errores es que esta bien configurado.

Ahora nos vamos a la configuracion del bucket y nos vamos a la parte de propiedades y en la parte de abajo donde nos dice alojamiento web pulsamos. 
Lo configuramos para que nos salga el alojamiento habilitado y pondremos que nos muestre el index. 
Nos dara una url en la que estara alojada nuestro, si accedemos con el enlace y nos sale la página ya estaria completa la S3