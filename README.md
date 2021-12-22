# Nombres-Coloridos
Este mod te permite cambiar el color de los nombres de los jugadores.

* Menú de lista de jugadores
* Categorias de Amigos/Enemigos en el menú
* Editar/Eliminar un Jugador desde el menú
* Selector de color para elegir el color del nombre de un jugador
* Comandos adicionales para agregar rápidamente un jugador, cambiar el color a un jugador, desactivarlos, etc.
* Agregar una nota a los jugadores que esten en agregados en el menú (útil para recordar quién te mató o a los miembros de tu banda)
# Instalación
* Extraer el archivo .zip con winrar y copiar todos los archivos y carpetas a la carpeta Moonloader
# Requerimientos
* SAMP 0.3.7
* SAMPFUNCS 5.4.1
* MOONLOADER 0.2.6.5 + Librerias 

# Instrucciones de uso
Tecla: 8 : Abre el menú principal para agregar, eliminar y editar los jugadores\
/col Abre el menú principal para agregar, eliminar y editar los jugadores

/cl Desactiva el mod, todos los jugadores del servidor se les pondra el color blanco por defecto, esta función de desactivar los colores se aplicará a todos los jugadores en el servidor, excepto a los jugadores que tengan el color del nombre azul de los policías que se puede cambiar con el comando /sapdcolor [ID de jugador]

/sapdcolor [ID de jugador] : El color del nombre de este jugador no sera eliminado por el comando /cl

/cla [ID Jugador] : Agrega al jugador a la lista de amigos del mod

/cle [ID Jugador] : Agrega al jugador a la lista de enemigos del mod

Las teclas y comandos pueden ser cambiados en el archivo de configuración--> Moonloader/Config/nombres_coloridos.ini\
[Settings]\
cmdAmigo=cla\
cmdEnemigo=cle\
cmdOnOff=cl\
tecla1=56\
tecla2=56\
cmd=col\
cmdcolorsapd=sapdcolor
* Puedes hacer copias de seguridad de tu listas de nombres copiando nombres_amigos.txt y nombres_enemigos.txt que se encuentran en GTASANANDREAS/Moonloader/config/
* No se debe agregar / en el archivo si deseas cambiar los comandos
* Códigos de teclas para reemplazar en el archivo de configuración ---> https://www.yoelprogramador.com/teclas-del-teclado-y-valores-de-codigos-de-tecla/

# Video
[![Watch the video](https://img.youtube.com/vi/T-D1KVIuvjA/maxresdefault.jpg)](https://youtu.be/auYZCkpPGHQ)
