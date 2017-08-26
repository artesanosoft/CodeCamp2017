
# Reto Code Camp 2017

El reto consiste en crear un servicio para usar el sistema de transporte metro dentro de la CDMX.

Se compondrá de 5 etapas sucesivas.

## Etapa 1

A partir el archivo .kml proporcionado, obtener la descripción de la todas las líneas del metro. Cada línea tiene un nombre y una lista de estaciones. Cada estación tiene un nombre y unas coordenadas geográficas (latitud y longitud). 

## Etapa 2

Basándose en la etapa anterior, crear un programa que a partir de los nombres de un par de estaciones, te de instrucciones precisas para trasladarte de una estación a otra, incluyendo todos los detalles necesarios para cada segmento de la ruta y los transbordes que hay que realizar en caso de que la ruta se componga de varios segmentos.

Para cada segmento debe indicar:

- estación de origen.
- estación destino.
- dirección en la que hay que abordar.
- número de estaciones que hay que viajar.

Los transbordos deben indicar a qué línea se debe dirigir para el nuevo segmento.

## Etapa 3

Exponer la funcionalidad anterior como un API REST

## Etapa 4

Crear una interfaz de usuario que permita utilizar este servicio.

## Etapa 5

Extender el servicio para que los usuarios puedan ingresar cualquier dirección de origen y destino, no solo estaciones del metro. El servicio les dará indicaciones sobre cómo llegar caminando a la estación del metro más cercana a su origen, después les dará instrucciones sobre como trasladarse usando el metro hasta la estación más cercana a su destino, y finalmente les indicará como llegar caminando de esta estación a su destino. 
