<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

# APRENDIZAJE NO SUPERVISADO

Índice y patrones de comportamiento a través de la aplicación de modelos de clusterización y análisis de componentes principales (PCA) sobre los datos relacionados con la criminalidad en Colombia durante el periodo comprendido entre los años 2017 y 2022

## Navegación

- [Datos](Datos)
- [Resultados Preliminares](Resultados%20Preliminares)
- [Documento de la Entrega](Documento%20de%20la%20Entrega)
- [Video Presentación](https://www.youtube.com/watch?v=51u8LV4H38Y)

## Datos

* Para el desarrollo de nuestro proyecto se descargaron las fuentes de delitos desde la página web del Ministerio de Defensa Nacional de Colombia (https://www.mindefensa.gov.co/irj/portal/Mindefensa/contenido?NavigationTarget=navurl://c17680c4c6ae25daaa589817c6ce4205 ) en donde cada uno de estos viene en archivos independientes, los cuáles fueron consolidados y se extraen los campos necesarios para cada variable.
Adicionalmente se descargó de la página web del Dane (https://geoportal.dane.gov.co/geovisores/territorio/consulta-divipola-division-politico-administrativa-de-colombia/) las coordenadas para geolocalización de los municipios.

## Resultados Preliminares

#### Gráfico de barras por año
<img src="./Resultados%20Preliminares/Grafico%20de%20barras%20por%20año.png" alt="Grafico de barras por añon" width="300" height="200">

#### Grafico de barras por delito
<img src="./Resultados%20Preliminares/Grafico%20de%20barras%20por%20delito.png" alt="Grafico de barras por delito" width="300" height="200">

* Se observa que de los últimos 6 años , el año 2020 fué el que presento menor cantidad de delitos (731.361) esto puede ser efectos de la pandemia de COVID en donde la mayoria de personas se encontraban en cuarentena la mayor parte del año, adicionalmente 2018 ha sdo el mes con mayor cantidad de delitos (790.434), sin embargo en los último 3 años del análisis se evidencia un crecimiento añoa a año.

* El hurto a personas es el delito que ha afectado en gran medida a la población en los últimos años siendo la categoría con mayor participación 1.619.489, seguido de lesiiones personales con 680.670 casos.

#### Clusters con PCA
<img src="./Resultados%20Preliminares/Clusters%20con%20PCA.png" alt="Latitud y longitud" width="300" height="200">

* Distribución del cluster luego de aplicar el PCA que tiene mejor ajuste.

## Documento de la Entrega

* La convivencia y seguridad ciudadana es un aspecto trascendental para la calidad de vida de una nación. Este aspecto se relaciona directamente con diversas variables sociales, económicas, políticas y culturales, de igual manera, su atención constituye uno de los retos más relevantes tanto del Gobierno nacional como de las entidades territoriales. La gestión territorial de la convivencia y seguridad ciudadana en Colombia se puede evidenciar a partir de la elaboración e implementación de la Política de Seguridad Nacional y a nivel territorial a través de los Planes Integrales de Seguridad y Convivencia Ciudadana (PISCC). Estos lineamientos permiten la construcción estrategias y lineamientos para la mejora de las condiciones de convivencia y seguridad ciudadana

* Colombia cuenta con ciertas particularidades respecto a los fenómenos y dinámicas que afectan las condiciones de convivencia y seguridad ciudadana. Estos fenómenos deben ser atendidos de forma diferencial, planteando estrategias claras y oportunas para reducir la ocurrencia de delitos, incentivar su seguimiento sostenible y, seguidamente, garantizar la retroalimentación continua en las decisiones de política pública.
 
* Por lo anterior, el presente documento pretende estructurar un Análisis por Componentes Principales y un Análisis por Clúster para caracterizar el comportamiento de las variables de seguridad entre 2017 y 2022 con la finalidad de establecer agrupamientos de los fenómenos de criminalidad de acuerdo con el municipio en el que se registren. El principal resultado del estudio es la alta incidencia de los hurtos (Hurto a personas, residencias, comercio y vehículos) y la extorsión y en una menor medida problemáticas como delitos ambientales, secuestro y homicidios colectivos ocurren en muy pocos municipios. Por lo que el análisis realizado demuestra la necesidad de generar estrategias que mitiguen el hurto como el factor principal de inseguridad en el país.

</body>
</html>



