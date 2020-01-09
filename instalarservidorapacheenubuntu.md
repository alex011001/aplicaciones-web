## INSTALAR EN UBUNTU 18.04 UN APACHE

###Introduccion Servidor APache

$sudo apt install apache2

$sudo fuser -vki /var/lib/dpkg/lock

$sudo ufw app list

$sudo ufw allow 'Apache'

$sudo ufw status

Ejercicio 1: Estamos en la empresa Gurú.com y alli nos han pedido que creemos una pequeña pagina web para probar el servidor el web, pero no tenemos interfaz grafica por loq eu tenemos que hacerlo desde consola.

&cd /
&cd var
&cd www
&sudo nano ejem.html
&sudo mv ejem.html .html
Para verlo pondremos en el buscador 127.0.0.1 y el nombre del archivo (127.0.0.1/ejem.html)

