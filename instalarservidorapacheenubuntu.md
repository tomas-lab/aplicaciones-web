## INSTALAR EN UBUNTU 18.04 UN APACHE

### introduccion Servidor Apache

1º Ejecutar el comando apt update para buscar actualizaciones

2º Ejecutar $ sudo apt install apache2

 Comando para el error “No se pudo bloquear /var/lib/dpkg/lock – open (11: Recurso no disponible temporalmente)”: 
 **sudo fuser -vki /var/lib/dpkg/lock**


sudo ufw app list: Este comando se utiliza para ver una lista de las aplicaciones asociadas al firewall de linux

sudo ufw allow 'Apache': Para añadir una regla al firewall
sudo ufw status: Para ver el estado del cortafuegos
sudo ufw enable: Para activar el cortafuegos

sudo systemctl stop apache2: Para detener el servidor
sudo systemctl start apache2: Para arrancar el servidor
sudo systemctl status apache2: Para ver el estado del servidor

sudo mkdir -p /var/www/nombredirectorio.com/public_html: este comando se utiliza para crear un directorio dentro de la carpeta /var/www

sudo cp 000-default.conf example.com.conf dentro de /etc/apache2/sites-available
sudo nano example.com.conf para configurar el fichero

sudo a2ensite example.com.conf
sudo a2dissite 000-default.conf







## EJERCICIO

Estamos en gurú.com y nos han pedido que creemos una pagina web para probar el servidor web pero no tenemos interfaz grafica y hay que hacerlo por consola.
