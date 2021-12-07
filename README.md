![](https://unal.edu.co/typo3conf/ext/unal_skin_default/Resources/Public/images/escudoUnal_black.png)

### Predicción de accidentabilidad en el municipio de Medellin en los años 2014 a 2019

En el presente trabajo se realiza el estudio descriptivo y de modelos predictivos de la accidentabilidad de movilidad en el municipio de Medellín, Colombia; Para la creación del modelo de predicción se tuvieron en cuenta los días festivos, los días de quincena, el día de la semana, la fecha del accidente.  También se realiza un agrupamiento para las comunas y barrios en base a su frecuencia de accidente, para esto se analizaron los accidentes que provocaron, muertes, lesiones o solo daños materiales; Los métodos analíticos que a continuación se detallan condujeron a una agrupación de riesgo alto, medio y bajo tanto para los barrios como para las comunas.

En base en esto se realizaron diferentes formas de representación descriptivas para realizar análisis como son:

-	Mapas
-	Diagrama de barras
-	Tablas


La serie de notebooks se realizo teniendo en cuenta las siguientes características de la base de datos del siguiente [link](http://medata.gov.co/dataset/incidentes-viales), donde se realizó una depuración de datos teniendo en cuenta variables que podrían llegar a tener una relación entre los datos y sirvieran para la predicción de estos mismos:

- Año
- Clase de accidente
- Diseño de vía
- Comuna
- Mes
- Latitud de donde ocurrió el accidente
- Longitud de donde ocurrió el accidente

Adicionalmente, se utilizó una base de datos adicional para hacer el delineamiento de las comunas del valle de aburrá para de esta forma saber en qué puntos son los más propensos en accidentabilidad, entres otros datos descriptivos [link](https://geomedellin-m-medellin.opendata.arcgis.com/datasets/l%C3%ADmite-catastral-de-comunas-y-corregimientos/explore?location=6.268500%2C-75.596100%2C12.09). 

- Comuna
- Área de la comuna
- Longitud de la comuna


#### Mapas,diagramas y analisis descriptivo 

Mapa de accidentabilidad en el municipio de Medellín en la temporada de 2014 a 2019:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/MapaMedellinComunas.png)

Cabe resaltar que las comunas más accidentadas del valle del aburra son:
- La Candelaria con un 20%
- Laureles con un 10%
- Castilla con un 10%

Esto se ve más claramente en el siguiente diagrama de barras:

 ![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/NumeroAccidentesMedellin.png)
 
Se nota claramente que la comuna más accidentada contiene casi el doble de accidente respecto sus dos seguidores, además se visualiza que en la otras comunas no son tan accidentadas.

Se realiza además el mapa de la clase de accidentalidad es decir la gravedad que las personas tuvieron un daño cuando sucedió este.

 
 ![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/ClaseAccidentalidadMedellin.png)
 
 Se ve claramente que más de la mitad de los accidentes ocurren daños personales, por tanto, se puede inferir en que se tiene una baja protección de los vehículos hacia las personas o se tiene poca cultura de seguridad en conducción de los vehículos. Además se tiene que la tasa de mortalidad por accidentes de tránsito es menor al 1% del total registrado siendo así que los vehículos automores protegen de la muerte en casi totalidad a sus usuarios.

Se tiene que en el periodo de 2015 a 2019 la accidentabilidad en Medellín se mantuvo constante, por tanto, no se han hecho efectivas los diferentes métodos de apaciguamiento de accidentes por medio de la educación vial; además en el 2020 se nota cambio brusco de disminución de la accidentabilidad debido confinamiento producido por pandemia del virus COVID-19.


![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/AccidentabilidadA%C3%B1o.png?raw=true)


En cuanto a la accidentabilidad se presenta en relacion a lo ocurrido cada año en las diferentes zonas de Medellin entre el 2014 y el 2019 y se llegaron a las siguientes conclusiones sobre accidente con mayor frecuencia, es decir, los choques dentro de Medellin:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/2014.jpeg)
- Se demuestran que el accidente más frecuente son los choques en 2014 con un porcentaje de 65.45% del total de accidentes ocurridos.
- Las cifras respecto al año 2014 tiene un aumento de 1,94% en choques.

- Los choques disminuyeron un 1,2% aproximadamente respecto al 2015 y sigue estando más alto un 0,8% respecto al 2014.

- Se sigue aumentando el porcentaje de choques año por año, un 2,4% respecto al 2016 y un 3,2% respecto al 2014.
 
- Se sigue aumentando el porcentaje de choques año por año, un 1,4% respecto al 2017 y un 4,6% respecto al 2014.

- Ha habido una rebaja significativa de accidentes por choques frente al año anterior del 2,8%, aunque sigue siendo mayor al año inicial un 1,8% aproximadamente.

Junto con el análisis se obtiene una tabla con las variables usadas frecuentemente para los diferentes gráficos expuestos anteriormente:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/frecuencia.jpeg)


La información presenta las variables con más frecuencia y los datos necesarios para obtener los porcentajes más altos de cada variable, para ser más claros, nos muestran que:

- En el lapso del los años 2014-2020 el año en el que más se presentaron accidentes viales fue el 2016 con un total de 47103 correspondientes al 17,4% de los accidentes totales.
- Los tipos de accidentes se han clasificado en 6 ('Choque', 'Atropello', 'Caída Ocupante', 'Volcamiento','Incendio', 'Otro'), de los cuales los que mayor frecuencia han tenido son los choques con un total de 180575, es decir el 66% de los accidentes en la ciudad de Medellín han sido por choques.
- En la base de datos se registraron 22 ubicaciones diferentes que han tenido accidentes dentro de la ciudad de Medellín, de ellos 52190 han sucedido en La Candelaria que corresponden al 19,3% de los accidentes totales.
- Hay tres diferentes niveles de gravedad clasificados para los accidentes viales ('Con heridos', 'Solo daños', 'Con muertos'), donde más de la mitad de los accidentes dejaron heridos, hay un registro de 150071 equivalentes al 55,4% de su totalidad.
- Algo importante que puede influir en el aumento de los accidentes viales es el diseño de las vías, 187319 de los accidentes registrados ocurrieron en el tramo de vía, equivalentes al 69,8% de los accidentes ocurridos entre los 13 diferentes diseños de vías.


### Modelos predictivos

Para la creación de los modelos de cada tipo de accidente se separo la base de datos en tres partes, entrenamiento, validación y evaluación. Para la base de datos de entrenamiento se tomaron los registros que van desde el año 2014 al 2017, mientras que para los de validación son los datos correspondientes a los años 2018 y 2019.

Por último, se dejó el año 2020 para la evaluación del comportamiento real del modelo antes datos no conocidos. Es importante comentar que como hipótesis se espera que el modelo no prediga correctamente para este año debido a que en el año 2020 hubo varias épocas de cuarentena total.

Todos los modelos tienen 7 características: Día, mes, año, día de la semana, quincena, festivo. La función de pérdida para evaluar el comportamiento del modelo es el RMSE, excluyendo aquellos modelos en los que existiese una diferencia de mas del 15% entre la base de datos de entrenamiento y las de testeo. Todas las bases de datos que se utilizaron para la predicción tanto de mes, semana o día se encuentran divididas en días que es la malla mas posible, esto explica en el hecho que como el objetivo es estimar una función desconocida resulta mas adecuado tener saltos de época lo mas fino posible.

Se presenta a continuación el análisis detallado del modelo predictivo para el modelo de choque, que es aquel que más frecuencia se presenta en la base de datos. Es importante recalcar que no se detallan los demás tipos de accidente porque su análisis es similar al de tipo de choque. Sin embargo, en los notebooks se presentan detalladamente el desarrollo.

### Modelo choque
El conjunto de datos de entrenamiento tiene una dimensión de 1277 filas y 7 columnas.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/Choque1.png)

Para la evaluación del modelo se codifican las variables categóricas.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/Choque2.png)

Para comparar los principales modelos que pueden arrojar los mejores resultados posibles, se hace uso de la librería pycaret de la cual se obtiene:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/Choque3.png)

Como se puede observar, todos los modelos exhiben características muy similares entre sí resaltando el Gradient Boosting Regressor, sin embargo, no hay una diferencia notable sobre los demás. Por tal motivo el modelo de Random forest regresor resulta tentador para su implementación debido a que este modelo sufre de ausencia de sobredimensionamiento, pero este se rechaza porque el modelo de regresión lineal muestra un comportamiento muy adecuado para la predicción y tiene características inferenciales, las cuales son ideales para disminuir la accidentalidad en la ciudad.

En la siguiente gráfica se presenta el nivel de importancia de las variables seleccionadas, como se aprecia todas las variables seleccionadas tienen una alta importancia porque a pesar de que se observa que las variables festivo, quincena y año se encuentra de relegadas en cuánto al día de la semana su valor es apreciable debido a la escala en la que se encuentra el eje.

#### Inferencia

- Coeficientes:

| Dia  | Mes  | Año | Festivo  |Quincena | Viernes  | Lunes  | Sabado| Domingo  | Jueves  | Martes| Miercoles | Intercepto |
|:---:|:---:| :-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| -0.434 | 2.000 | 2.21 | -9.13| -0.828| 4.56 |2.0631| -02972 |  -12.4 |    1.63| 2.90  | 2.000  | 78.46 |
 
 Las unidades de los coeficientes para las variables son:  <img src="https://render.githubusercontent.com/render/math?math=choque/x"> donde <img src="https://render.githubusercontent.com/render/math?math=x">  es según corresponda. Para la variable Quincena corresponde a <img src="https://render.githubusercontent.com/render/math?math=Choques/Quincenas">.
 
 En promedio hay 78 accidentes tipo choque al día, sin embargo, los días como viernes y lunes se exhibe un aumento en el número de accidentes, una hipótesis para explicar este fenómeno podría ser por el hecho que los viernes las personas pueden exhibir un cansancio acumulado por la semana laborada. Otra hipótesis para explicar lo del día de lunes podría ser que las personas una reducción en su estado de alerta por los días de descanso presentados previamente.
 
Como es de esperar los domingos y festivos la movilidad en Medellín es bastante rápida debido a la poca cantidad de autos en las calles lo que reduce la cantidad de choques en Medellín.

#### Comportamiento del modelo

Luego de sintonizar los parámetros para la creación del modelo, en este caso el del modelo lineal se obtuvieron los siguientes RMSE.

| Entrenamiento| Tests| Evaluacion|
| --- | --- | --- |
| 13.08 Choque | 14.82 Choque | 46.18 Choque|

Como se observa no hay sobredimensionamiento en la creación del modelo por lo cual se considera que el modelo tiene la capacidad para predecir valores futuros para otros años a pesar de que el comportamiento en la evaluación es deficiente pues este resultado era de esperar pues el 2020 fue un año atípico por la presencia de épocas con marcada cuarentena.


### Cluster

Se busca agrupar los barrios de Medellín en base a su accidentalidad. El agrupamiento busca identificar aquellos barrios en los que es mas frecuente los accidentes y con base en estos se tomar acciones de control para evitar el aumento de estos.

Para la realización del cluster se crearon características que identificaran las descripciones de cada barrio.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/Barrio1.png)

Luego de la normalización de los datos se obtiene:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/Barrio2.png)

Para el clúster se realiza un ordenamiento jerárquico, con el método Ward que busca minimizar la varianza del algoritmo. El dendograma obtenido es:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/Barrio3.png)

Para reducir el error humano que se puede causar cuando se desea estimar cual puede ser el agrupamiento óptimo a partir de la visual del dendograma se utiliza el método del codo.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/Barrio4.png)

Se observa que el quiebre mas pronunciado en la gráfica es cerca de los dos o tres cluster, sin embargo, la primera se descarta pues dos clusters son pocos para diferenciar correctamente los barrios en Medellín.

El proceso realizado indica:

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/Barrio5.png)

* *El grupo 0*: Es el grupo con menor accidentes, por lo tanto, este grupo corresponde a los barrios con menor riesgo. En la gráfica que se presenta a continuación correspondo al punto azul.

* *El grupo 1*: Son los barrios con mayor frecuencia de accidentes, por lo cual indican un riesgo alto. En la gráfica se presenta con el color rosado.

* *El grupo 2* : Son aquellos barrios que tienen un riesgo medio de accidente.

![](https://github.com/Universidad-Nacional-TAE/Primer-trabajo-TAE/blob/main/Images/Barrio6.png)

Se realizó el agrupamiento por comunas, los cuales se presentan en el Notebook.

### Conclusiones

Los meses que mayor presentaron accidentes son diciembre y agosto, lo que corresponde con los valores esperados pues en diciembre hay varias celebraciones y el aumento del comercio es notorio por esas fechas lo cual indica mayor presencia de autos en la calle. Para el mes de agosto se presenta un aumento significativo en el total de accidentes y esto concuerda con la feria de flores que se realiza en Medellín.

Los barrios que presentan mayor accidentalidad se encuentran por toda la línea central de Medellín, lo que indica que el flujo vehicular es alto por estos territorios.

El compromiso por el registro de los datos es una materia prima para la mejora continua, pues a partir de ellos se pueden generar acciones de controles que permitan disminuir accidentes.

### Critica de trabajo y acciones futuras

El trabajo desarrollado presenta bases sólidos para predecir los accidentes de la ciudad, sin embargo, dado el conocimiento de la región se podría buscar un análisis mayor al ingresar variables como el clima en Medellín pues se evidencia un aumento de los choques en la ciudad cuando hay lluvia sobre el territorio. Otro aspecto que podría ser interesante es evaluar como se comporta el tránsito en Medellín cuando sufre las épocas de polución. 

Dado la cantidad desbalanceada de tipo de accidentes se sospecha que no hay un real compromiso para detallar el tipo de accidentes, por lo cual se podría generar consciencia a través de los organismos encargados de realizar el registro del valor que tiene un dato.

En cuánto a la aplicación se podría mejorar el proyecto generando un indicativo que indique dada las características del momento o de determinado tramo de la ciudad cual prediga que tipo de accidentes es mas probable que tenga, es decir, clasificar dada las características del sector o la hora.


### Aplicación Web 

Se realizó una aplicación web para mostrar los diferentes modelos y gráficas en tiempo real de los datos de la accidentabilidad en el municipio de Medellín, para que de esta forma el público libre pueda visualizar los datos y modelos predictivos.[link](https://e4r3as.herokuapp.com/)

### Bibliografia

- [Stack overflow](https://stackoverflow.com/)
- [Pandas](https://pandas.pydata.org/)
- [Geopandas](https://geopandas.org/en/stable/)
- [Scikit learn](https://scikit-learn.org/stable/)
- [Dashboard with python](https://towardsdatascience.com/dash-for-beginners-create-interactive-python-dashboards-338bfcb6ffa4)
- [Limpieza de datos](https://aprendeia.com/limpieza-y-procesamiento-de-datos-con-codigo-en-python/)
