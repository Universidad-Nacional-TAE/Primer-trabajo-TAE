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


Junto con el analisis se obtiene una tabla con las variables usadas frecuentemente para los diferentes graficos expuestos anteriormente:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/b23ce64b62f48faf56159409a1acad8bfbc05c20/Images/describe.jpeg)
De este, la informacion se nos presenta las variables con mas frecuencia y la informacion necesaria para obtener los porcentajes mas altos de cada variable, para ser más claros , nos muestran que:

- En el lapso del los años 2014-2020 el año en el que mas se presentaron accidentes vieles fue el 2016 con un total de 47103 correspondiente al 17,4% de los accidentes totales.
- Los tipos de accidentes se han clasificado en 9 (), de los cuales los que mayor frecuencia han tenido son los choques con un total de 180575, es decir el 66% de los accidentes en la ciudad de Medellin han sido por choque.
- En la base de datos se registraron 22 ubicaciones diferentes que han tenido accidentes dentro de la ciudad de Medelliín, de ellos 52190 han sucedido en La Candelaria que corresponden al 19,3% de los accidentes totales.
- Hay cuatro diferentes niveles de gravedad clasificados para los accidentes viales (), donde más de la mitad de los accidentes dejaron heridos, hay un registro de 150071 equivalentes al 55,4% de su totalidad.
- Algo importante que puede influir en el aumento de los accidentes viales es el diseño de las vias, 187319 de los accidentes registrados ocurrieron en los tramo de via, equivalentes al 69,8% de los accidentes ocurridos etre los 13 diferentes diseños de vias.

### Modelos predictivos
