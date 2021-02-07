# TRabajoFinalDAPW
 tarea final del modulo de desplegamiento

## Comenzando 🚀

Este proyecto muestra como desplegar una pagina web con un servidor Apache.

Lo despliego primero mediate un protocolo no seguro http, y en una segunda parte ya con https, generando los certificados necesarios y autofirmados para ello.



### Pre-requisitos 📋

Debes tener instalado apache2, openssl y activado el modulo ssl de apache.

### Instalación 🔧
Debes generar una estructura de carpetas acorde para el funcionamiento de la aplicacion:

- EL index.html lo tendras ubicado dentro de las carpetas "empresa-actividad-daw/html" y "empresa-actividad-daw-ssl/html" que estaran en el directorio /var/www/

- Los archivos de configuración estaran dentro /etc/apache2/sites-available con los nombres empresa-actividad-daw.conf y empresa-actividad-daw-ssl.conf

- Una vez creados recordad ejecutar el comando a2ensite sobre estos para que sean activados.

## Ejecutando las pruebas ⚙️

Para probarlo se reinicia el servidor y  se abre el navegador que debería abrir sin problema. 


## Construido con 🛠️

- Visual Studio Code
- Apache2
- Debian 10

