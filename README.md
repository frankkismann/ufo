# ufo
Demo de video juego de plataformas, sin motor o engine de física, sino que utilizando sólo librerías gráficas y de sonido para la manipulación de hojas de sprite en canvas y mp3. Las librerías utilizadas son Easeljs y Soundjs.

# Directorios
La demostración cuenta con los siguientes directorios:

* imagenes: contiene fondos y hojas de sprite para la animación del personaje principal y objetos en el juego
* js: toda la lógica del juego está aquí. Las funciones principales, la manipulación de teclado, el control de sonido y la detección de colisiones están controladas aquí.
* sonido: almacenamiento de archivos mp3 para los efectos de sonido dentro de la demostración. 

# Archivo index.html
Archivo encargado de ejecutar constantemente el LOOP del juego. Éste ciclo se encuentra constantemente consultando todas las variables del juego y evaluando cada evento asociado al personaje principal y a sus enemigos.
