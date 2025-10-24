# guestbook_php

Aplicación guestbook escrita en PHP.

## Instalación

1. Instala un servidor LAMP. Además es necesaria la librería `php-mbstring`.
2. Crea un una base datos y ejecuta el fichero `schema.sql` para crear las tablas.
3. Crea un virtualhost y copia los ficheros en el DocumentRoot.
4. Activa el modulo **rewrite** y configura el servidor para que podamos usar ficheros .htaccess.