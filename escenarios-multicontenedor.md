# Ejercicio de escenarios multicontenedor - Docker

----

Vamos a desplegar una tienda virtual construída con **prestashop**

1. Creamos un directorio con el nombre de prestashop, y dentro cremos un fichero docker-compose.yml con la siguiente configuración:

![](Imagenes/EjercicioCinco/1.png)

2. Levantamos los servicio de **prestashop** y **mariadb** con ```docker-compose up -d```:

![](Imagenes/EjercicioCinco/1.1.png)

3. Y comprobamos que estan funcionando:

![](Imagenes/EjercicioCinco/1.2.png)

4. Por último accedemos desde el navegador a la aplicación:

![](Imagenes/EjercicioCinco/2.png)