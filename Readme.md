# Periodismo de datos

## Comandos
- `mk dir`: crear un directorio
- `ls`: saber lo que hay dentro de un directorio/carpeta determinada
- `cd`: ir a un directorio
- `nano`: es un editor de textos en la consola, un editor de textos CLI que nos aporta velocidad y precisión
- `cat`: muestra el contenido de la pantalla. Hay que tabular, no darle a enter, para que funcione
- `du -sh ~/carpeta/`: conocer la capacidad que ocupa un directorio/carpeta que hay en el directorio
- `touch`: crear un archivo, en formato `.txt`
- `rm -r`: borrar cualquier archivo
- `Echo "texto" > archivo`: añadir texto al archivo
- `Echo "texto2" >> archivo`: añadir contenidos. Son dos fechas porque sino pisa el contenido que hay dentro del archivo

## Cambiar la home de Cygwin
Es decir, cómo pasar del espacio que tiene creado *Cygwin* en el terminal  a nuestro espacio de Windows, con el objetivo de tener acceso a nuestro directorio, es decir, en nuestro usuario ahora podremos crear carpetas, borrar o manipularlas a través de *Cygwin*.

Por defecto, la home del usuarix de *Cygwin* es el directorio de instalación del programa.
para disfrutar de *Cygwin* y acceder a todo el disco, debemos modificar la variable `db_home` en `/etc/nsswitch.conf` con nuestro editor `nano` y escribimos `db_home: windows`:

La almohadilla `#` que aparece al principio de línea significa que la línea está comentada, es decir, que no la va a leer el programa que quiera leerla para hacer algo.
