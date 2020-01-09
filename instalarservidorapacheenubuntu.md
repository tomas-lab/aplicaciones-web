## INSTALAR EN UBUNTU 18.04 UN APACHE

### introduccion Servidor Apache

1º Ejecutar el comando apt update para buscar actualizaciones

2º Ejecutar $ sudo apt install apache2

 Comando para el error “No se pudo bloquear /var/lib/dpkg/lock – open (11: Recurso no disponible temporalmente)”: 
 **sudo fuser -vki /var/lib/dpkg/lock**
