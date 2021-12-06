![](https://unal.edu.co/typo3conf/ext/unal_skin_default/Resources/Public/images/escudoUnal_black.png)
### Predicción de accidentabilidad en el municipio de Medellin en los años 2014 a 2019

La serie de notebboks siguientes se realizo el estudio descriptivo y de modelos predictivos de la accidentabilidad de movilidad en el municipio de Medellin,Colombia; teniendo en cuenta las siguientes caracteristicas de la base de datos del siguiente [link](http://medata.gov.co/dataset/incidentes-viales), donde se realizo una depuración de datos teniendo en cuenta variables que podrian llegar a tener una relacion entre lo datos y sirvieran para la predicción de estos mismo:

- Año 
- Clase de accidente
- Diseño de via
- Comuna
- Mes
- Latitud de donde ocurrio el accidente
- Longitud de donde ocurrio el accidente

Adicionalmente se utilizo una base de datos adicional para hacer el dileneamiento de las comunas del valle de aburra para de esta forma saber en que puntos son los mas propensos accidentabilidad, entres otros datos descriptivos [link](https://geomedellin-m-medellin.opendata.arcgis.com/datasets/l%C3%ADmite-catastral-de-comunas-y-corregimientos/explore?location=6.268500%2C-75.596100%2C12.09). 

- Comuna
- Area de la comuna
- Longitud de la comuna

En base en esto se realizaron diferentes formas de representacion descriptivas para realizar analisis como son:
- Mapas
- Diagrama de barras 
- Tablas

#### Mapas,diagramas y analisis descriptivo 

Mapa de accidentabilidad en el municipio de Medellin en la temporada de 2014 a 2019:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/MapaMedellinComunas.png)

Cabe resaltar que las comuna mas accidentadas del valle del aburra son:
 - La Candelaria con un 20%
 - Laureles con un 10%
 - Castilla con un 10%
 
 Esto se ve mas claramente en el siguiente diagrama de barras:
 
 ![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/NumeroAccidentesMedellin.png)
 
 Se nota claramente que la comuna mas accidentada contiene casi el doble de accidente respecto sus dos seguidores, ademas se visualiza que en la otras comunas no son tan accidentadas.
 
 Se realiza ademas el mapa de la clase de accidentalidad es decir la gravedad que las personas tuvieron un daño cuando sucedio este.
 
 ![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/ClaseAccidentalidadMedellin.png)
 
 Se ve claramente que mas de la mitad de los accidentes ocurren daños personales por tanto se puede inferirir en que se tiene una baja protección de los vehiculos hacia las personas o se tiene poca cultura de seguridad en conduccion de los vehiculos. Ademas se tiene que la tasa de mortalidad por accidentes de transito es menor al 1% del total registrado siendo asi que los vehiculos automores protegen de la muerte en casi totalidad a sus usuarios.
 
Se tiene que en el periodo de 2015 a 2019 la accidentabilidad en Medellin se mantuvo constante por tanto no se han hecho efectivas los diferentes metodos de apciguamiento de accidentes por medio de la educacion vial; ademas en el 2020 se nota cambio brusco de disminución de la accidentabilidad debido confinamiento producido por pandamia  del virus COVID-19.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/AccidentabilidadA%C3%B1o.png?raw=true)


En cuanto a la accidentabilidad se presenta en relacion a lo ocurrido cada año en las diferentes zonas de Medellin entre el 2014 y el 2019 y se llegaron a las siguientes conclusiones sobre accidente con mayor frecuencia, es decir, los choques dentro de Medellin:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/2014.jpeg)
- Se demuestran que el accidente más frecuente son los choques en 2014 con un porentaje de 65.45% del total de accidentes ocurridos.
![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/2015.jpeg)
- Las cifras respecto al año 2014 tiene un aumento de 1,94% en choques.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/2016.jpeg)
- Los choques disminuyeron un 1,2% aproximadamente respecto al 2015 y sigue estando más alto un 0,8% respecto al 2014.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/2017.jpeg)
- Se sigue aumentando el porcentaje de choques año por año, un 2,4% respecto al 2016 y un 3,2% respecto al 2014.
 
![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/2018.jpeg)
- Se sigue aumentando el porcentaje de choques año por año, un 1,4% respecto al 2017 y un 4,6% respecto al 2014.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/2019.jpeg)
- Ha habido una rebaja significativa de accidentes por choques frente al año anterior del 2,8%, aunque sigue siendo mayor al año inicial un 1,8% aproximadamente.


Junto con el analisis se obtiene una tabla con las variables usadas frecuentemente para los diferentes graficos expuestos anteriormente:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/frecuencia.jpeg)


La informacion presenta las variables con mas frecuencia y los datos necesarios para obtener los porcentajes mas altos de cada variable, para ser más claros , nos muestran que:

- En el lapso del los años 2014-2020 el año en el que mas se presentaron accidentes vieles fue el 2016 con un total de 47103 correspondiente al 17,4% de los accidentes totales.
- Los tipos de accidentes se han clasificado en 6 ('Choque', 'Atropello', 'Caida Ocupante', 'Volcamiento','Incendio', 'Otro' ), de los cuales los que mayor frecuencia han tenido son los choques con un total de 180575, es decir el 66% de los accidentes en la ciudad de Medellin han sido por choques.
- En la base de datos se registraron 22 ubicaciones diferentes que han tenido accidentes dentro de la ciudad de Medelliín, de ellos 52190 han sucedido en La Candelaria que corresponden al 19,3% de los accidentes totales.
- Hay tres diferentes niveles de gravedad clasificados para los accidentes viales ('Con heridos', 'Solo daños', 'Con muertos'), donde más de la mitad de los accidentes dejaron heridos, hay un registro de 150071 equivalentes al 55,4% de su totalidad.
- Algo importante que puede influir en el aumento de los accidentes viales es el diseño de las vias, 187319 de los accidentes registrados ocurrieron en los tramo de via, equivalentes al 69,8% de los accidentes ocurridos etre los 13 diferentes diseños de vias.

### Modelos predictivos

#### Cluster

Se realizo una agrupación por barrios por la peligrosidad de accidentabilidad por medio de datos de la gravedad de los accidentes de transito clasificados por  muertos, daños y heridos,ademas del numero de accidentes cada uno de estos por cada de barrio de Medellin; donde se realizo la sumatoria de cada barrio de estas caracteristicas para luego sacar la media y normalización.

#### Algoritmo de k-means

Para obtener el numero de k mas optimo con los datos antes descritos se relaliza el metodo del codo donde se mide la distancia entre los centroides hallados con respecto a los datos, para de esta forma obtener el score donde el mas optimo seria de 1, para este caso se obtuvo un valor de k = 3.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/KBarrio.png)

Ya teniendo este k se realizo el algoritmo de k- mean para seccionar por peligrosidad de accidentabilidad de movilidad, este cluster se definio de la siguiente manera:

- 1 : Alto riesgo de accidentes y peligro. Peligro alto 
- 2 : Peligro moderado. Peligro Medio 
- 0 : Peligro bajo de accidentes. Peligro bajo

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/ClusterBarrio.PNG)

Con esto ya se quiere representar por medio de un grafico geografico la representacion puntual en el mapa de estos cluster de cada barrio por peligrosidad. 

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/ClusterMapa1.png)

Obteniendo esto se puede concluir que los barrios mas accidentables y peligrosos para los conductores se encuentran en la cercania de las vias principales y sus cercanias; ya en el nivel de peligorsidad se encuentran la gran mayoria de barrios de la ciudad de Medellin donde se puede concluir que aunque no es un riesgo total movilizarse en la ciudad se debe tomar una preocuación en la movilidad ya que se tiene una tasa ya admitible de accidentes que pueden occurrir.

### Aplicación Web 

Se realizo una aplicación web para mostrar los diferentes modelos y graficas en tiempo real de los datos de la accidentabilidad en el municipio de Medellin, para que de esta forma el publico libre pueda visualizar los datos y modelos predictivos.[link](https://e4r3as.herokuapp.com/)
