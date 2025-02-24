# Acerca de mí

Ingeniero Mecatronico certificado en Data Sciecne con experiencia en extracción, limpieza y creacion de modelos predictivos mediante machine learning.

Genero insights con información, genero modelos predictivos, para apoyar en la toma de decisiones y apoyar en procesos, reduciendo tiempo y automatizando procesos, logrando un significativo ahorro de tiempo.

## Habilidades tecnológicas
- Analisis y gestion de datos **Excel | SQL | Python**
- Machine Learning 

## Habilidades blandas

Analisis de datos | Resolución de problemas | Comunicación efectiva | Organización | Proactivo | Autodidacta | Adaptabilidad | Trabajo en equipo | 
# Proyectos seleccionados

## Mega Line
Es sistema de recomendacion de nuevos servicios para usuarios de una compañia telefonica, debido a que gran cantidad de usuarios cuentas con paquetes los cuales son heredados y ya tienen mucho tiempo con el mismo servicio. 
**Un modelo de recomendacion de servicios para los usuarios de MegaLine.**

#### Herramientas y tipo de proyecto
- Python 
- Pandas
- Seaborn
- scikit-learn
- Limpieza de datos
- Transformación de datos
- Analisis de datos
- Modelos de predicción

### Preguntas clave

1. ¿Cual es el comportamiento de los nuevos usuarios?
2. ¿Que diferencia hay entre los usuarios que tienen diferentes servicios?
3. ¿Como podemos segmentar cada usuario?

### Metodología

- **Preporecesameint de datos** Se limpiaron los datos, eliminamos inconsistencias y verificamos ausencia de duplicados y valores faltantes.
- **Explorartory Data Analysis (EDA)** Se analizaron caracteristicas demograficas y de uso, identificando patrones en los clientes.
- **Modelo predictivo** Se entrenaron modelos con regresion logistica, bosque aleatorio y arbol de decisiones.

### Conclusiones y recomendaciones

#### Entramiento de los modelos
Todos los modelos nos dieron un score arriba de 85% exceptuando el de regresion logistica el cual esta en %65.


#### Estrategias recomendadas

Los usuarios ultras tienden a usar mas de los servicios pero son menos personas que los usuarios normales.

### Visualizaciones destacadas
![User Box Chart](assets/img_megaline.png)
![Scatter Chart](assets/img_megaline_users.png)

## Smart-Retention
Hay una disminusion de usuarios y el equipo de marketing esta realizando investigación de los posibles causantes, del cual contamos con bastante información.

#### Herramientas y tipo de proyecto
- Python
- Pandas
- Seaborn
- scikit-learn
- Limpieza de datos
- Transformación de datos
- Analisis de datos
- Modelos de predicción

### Preguntas clave
1. ¿Cuales son los comportamiento de los usuarios que mas cancelan el servicio?
2. ¿Que diferencia a los clientes leales de los que abandonan?
3. ¿Como se puede segmentar los clientes para diseñar estrategias personalidas?

### Metodologia

- **Preporecesameint de datos** Se limpiaron los datos, eliminamos inconsistencias y verificamos ausencia de duplicados y valores faltantes.
- **Unión de bases de datos** Debido a que tenemos varias fuentes de información se juntaran para poder sacar el mayor provecho a los datos.
- **Explorartory Data Analysis (EDA)** Se analizaron caracteristicas demograficas y de uso, identificando patrones en los clientes.
- **Modelo predictivo** Se entrenaron modelos como bosque aleatorio, arbol de decisiones, potenciación de gradiante (LightGBM).

### Conclusiones y recomendaciones

#### Comportamiento de usuarios, Ventas y Marketing
- Los usuarios los cuales cuentan con el servicio de pago mensual tienen mayor tendencia a abandonar el servicio.
- Los usuarios que pagan mes con mes tienden a tener mas variacion en los pagos.

#### Recomendaciones:
- Dar mayor atención a los usuarios que pagan mensualmente.
- Checar si los usuarios requieren de los servicios que estan pagando.
- Segregar mejor los paquetes y los costos.
- Los primeros meses es donde se encuentra la mayor taza de bajas en el servicio.

### Visualizaciones detacadas
![User Box Chart](assets/img_smart_retention.png)


## Oil Spot Finder
Una empresa quiere realizar una inversión en la escabacion de pozos petroleros, los cuales cuentan con información de los espacios a escarbar. Quieren saber cuales son las areas las cuales les presentarian mayor numero de ganancia.

#### Herramientas y tipo de proyecto
- Python
- Pandas
- Seaborn
- scikit-learn
- Limpieza de datos
- Transformación de datos
- Analisis de datos
- Modelos de predicción

### Preguntas claves
1. ¿Que area presenta mayor retorno de inversión?
2. ¿Cuales tierras presentan mayor consistencia en los datos?
3. ¿Cual es el calculo de riesgo y ganancias para cada región?

### Metodología
- **Preporecesameint de datos** Se limpiaron los datos, eliminamos inconsistencias y verificamos ausencia de duplicados y valores faltantes.
- **Unión de bases de datos** Debido a que tenemos varias fuentes de información se juntaran para poder sacar el mayor provecho a los datos.
- **Explorartory Data Analysis (EDA)** Se analizaron caracteristicas demograficas y de uso, identificando patrones en los clientes.
- **Modelo predictivo** Se entrenaro un modelo de regresíon lineal

### Conclusiones y recomendaciones

#### Comportamiento de las regiones

#### Recomendaciones:
- Hay dos regiones las cuales reportan mayor retorno de inversión.
- El error cuadratico de las regiones no es tan elevado para que presente un riesgo para la inversión.
- La discrepacia de retorno es muy minima presentando un riesgo y ganancia bajo.

### Visualizaciones detacadas

![Informacion Region 1](assets/img_geo1.png)
![Informacion Region 2](assets/img_geo2.png)
![Informacion Region 3](assets/img_geo3.png)
![PLot chart](assets/img_geodata.png)