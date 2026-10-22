# Practica 4

## Preparación
Para empezar, creamos un nuevo repositorio vacío para nuestra practica
![Imagen1](imagenes/1.png)
<br><br>

Además de crear un archivo nuevo HTML y añadirle un par de líneas básicas
![Imagen2](imagenes/2.png)
<br><br>

## Desarrollo
Creamos las ramas necesarias y comprobamos que, efectivamente, se han creado
![Imagen3](imagenes/3.png)
<br><br>
![Imagen4](imagenes/4.png)
<br><br>

A continuación voy a trabajar en cada rama creada añadiendo un archivo HTML a cada una y haciéndole un commit a los archivos creados para guardarlos
<br>

Rama cabecera: <br>
![Imagen5](imagenes/5.png)
<br><br>

Rama contenido: <br>
![Imagen6](imagenes/6.png)
<br><br>

Rama pie: <br>
![Imagen7](imagenes/7.png)
<br><br>

Ahora vamos a combinar todas las ramas en la rama main con el comando "merge" (solo se ve un merge hecho porque no hice captura pero se ve que están todos los archivos) <br>
![Imagen8](imagenes/8.png)
<br><br>

Luego unificamos el código de todas las ramas en el index
![Imagen9](imagenes/9.png)
<br><br>

Guardamos los cambios y borramos las ramas anteriores porque ya no nos hacen falta
![Imagen11](imagenes/11.png)
<br><br>

## Simulación de conflicto
Creamos un nueva rama donde modificamos la etiqueta "h1" del archivo index
![Imagen12](imagenes/12.png)
<br><br>

Después juntamos la rama rediseño a la rama main y vemos que nos sale un error de conflicto al intentar añadir un "h1" cuando la página original de la rama main ya tenía uno, modificamos el archivo y guardamos
![Imagen13](imagenes/13.png)
<br><br>

## Git log final
Aquí vemos todos los git logs hechos de forma más comoda en modo de gráfico
![Imagen14](imagenes/14.png)
<br><br>
