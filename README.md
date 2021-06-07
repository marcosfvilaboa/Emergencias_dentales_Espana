# Emergencias_dentales_Espana
Proyecto de la UOC sobre visualización de datos. Datos de encuestas a odontólogos sobre emergencias dentales en el confinamiento por COVID-19


# To-Do
Este trabajo pretende mostrar el proceso de elaboración de una visualización de datos a partir del dataset "[Dental emergency care in Spain during the state of alarm due to COVID-19 pandemic](https://edatos.consorciomadrono.es/dataset.xhtml?persistentId=doi:10.21950/3STT2Q)" 

## Visualización de datos

La visualización se puede consultar en [Flourish Studio - Public Website](https://public.flourish.studio/visualisation/6356390/). 

Su objetivo es mostrar, de manera interactiva, el modo de operar de los odontólogos durante el confinamiento por la pandemia del COVID-19 asi como el comportamiento de la población -pacientes- en el uso de este servicio. 


[![Visualization](./img/dental_emergencies_Spain.png)](https://public.flourish.studio/visualisation/6356390/)

## Datos

Los datos utilizados forman parte del conjunto de datos proporcionados por el portal de datos abiertos del [consorcio madroño](http://www.consorciomadrono.es/investigam/)

- [data](./data): ficheros de datos utilizados para la construcción de la visualización.
  - [LA ATENCI N DE LAS URGENCIAS ODONTOL GICAS EN ESPA A DURANTE EL ESTADO DE ALARMA DEBIDO AL COVID-19.tab](./data/LA ATENCI N DE LAS URGENCIAS ODONTOL GICAS EN ESPA A DURANTE EL ESTADO DE ALARMA DEBIDO AL COVID-19.tab): datos originales.
  - [dental_emergencies_edited.tab](./data/dental_emergencies_edited.tab): modificación del fichero original (nombre de las columnas).
  - [dental_emergencies.csv](./data/dental_emergencies.csv): datos modificados base de la visualización.
  - [CCAA_lat_lon.csv](./data/CCAA_lat_lon.csv): Tabla con la geolocalización de puntos en las comunidades autònomas para visualizarlos en el mapa.
- [docs](./docs): documento PDF con el informe. 
  - [FernandezVilaboaMarcos_VD_Practica.pdf](./docs/FernandezVilaboaMarcos_VD_Practica.pdf)
- [img](./img): imagenes relativas a la visualització
  - [dental_emergencies.jpg](./img/dental_emergencies.jpg): Captura de la visualización
  - [Spain_map_equirectangular_projection.png](./img/Spain_map_equirectangular_projection.png): Mapa de españa equirectangular para la proyección geolocalizada.
- [src](./src): ficheros para la construcción de la visualización.
  - [transformation.ipynb](./src/transformation.ipynb): Jupyter Notebook con el código para la limpieza y transformación de los datos.

----
