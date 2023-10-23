<div align="center">

# **Proyecto Nro 1 - Sharks attaks** </div>
![Imagen](https://i.postimg.cc/6qxVTBVT/Sharks.webp)](https://postimg.cc/dknZxPxK)

---

#### <div align="center">**He basado mi limpieza de datos para saber cuál era el país con mas ataques de tiburones en un rango entre 15 y 60 años de edad y la estación del año en la que eran mas frecuentes.

Para ello primero revisamos las dimensiones de nuestra data, constaba de 25.723 filas y 24 columnas.

Luego revisamos y eliminamos todas las filas con valores nulos, quedando con 6.302 filas.

Posteriormente revisamos las columnas con valores nulos para poder filtrar lo que bajo nuestro criterio, sería necesario.

En este caso, los valores nulos en la columna nombre, los dejamos como desconocidos, ya que no es relevente para mi análisis.

Continuamos asignando valores de 'unknown' que luego procedimos a investigar, como en la columna 'Fatal (Y/N)' que pudimos rellenar de acuerdo a la información descrita en la columna 'Injury'.


Aplicamos funciones para la limpieza de datos, por ejemplo en la columna 'Sex' se repetían categorías con M y F pero algunas estaban en minúsculas.

Eliminamos las filas que no poseían la fecha del ataque, ya que para mi criterio y objetivo, era un dato necesario.

Elaboré una función de acuerdo a la fecha del accidente y el país, para saber la estación del año en la que sucedió y la agregamos en una columna nueva llamada Season.

Luego de nuestro análisis, podemos concluir que:

-El país con mas ataques de tiburones es Estados Unidos pero el país con mayor número de muertes a causa de estos ataque es Australia
-Nro de accidentes USA: 1.073
-Nro de accidentes Australia: 555
-Edad promedio: 28 años
-Fallecidos USA: 61
-Fallecidos Australia: 147
-Estación donde sucedieron mas ataques: En USA ha sido durante el verano y en Australia en primavera.
 ** </div>

&nbsp;
