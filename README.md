# Instalar-Nessus-en-Kali

<h2>Guía para instalar Nessus en Kali</h2>

<h3>¿Qué es Nessus?</h3>

<b>Nessus</b> es una herramienta de <b>evaluación de vulnerabilidades</b> desarrollada por <b>Tenable, Inc.</b>
Nessus analiza redes, servidores, aplicaciones y otros sistemas en busca de posibles debilidades que podrían ser explotadas por atacantes.


<h2>Descargar Nessus</h2>
En tu Kali, usa el navegador web (Firefox) para descargar Nessus mediante este <a href="https://www.tenable.com/downloads/nessus"=blank>enlace.</a>
Selecciona la distribución de Linux adecuada (Debian/Kali) como se muestra en la imagen de abajo.


<img src="Pictures/Pic 1.jpg">

Ve a la carpeta donde se encuentra el archivo <strong><i>.deb</i></strong> y haz clic derecho dentro de la carpeta para seleccionar <b>abrir terminal aquí</b>, como se muestra en la imagen de abajo.


<img src="Pictures/Pic 2.jpg">


Una vez en la terminal, ejecuta el comando <b><i>sudo dpkg -i "filename".deb</i></b> para instalar Nessus. (Reemplaza filename por el nombre del archivo de Nessus).
<p>Después de instalarlo, inicia el servicio de Nessus ejecutando el comando <b><i>systemctl start nessusd</i></b>.</p>
<p>Confirma si el servicio de Nessus está activo ejecutando el comando <b><i>systemctl status nessusd</i></b>.</p>
<p>Una vez que esté activo, abre el navegador web en Kali (Firefox) y escribe <b><i>https://kali:8834</i></b> o haz clic directamente en el enlace que aparecerá en la parte inferior después de ejecutar el <b>comando de inicio</b>, como se muestra abajo.</p>


<img src="Pictures/Pic 3.jpg">


