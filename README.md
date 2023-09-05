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

## Datos

Para el desarrollo de nuestro proyecto se descargaron las fuentes de delitos desde la página web del Ministerio de Defensa Nacional de Colombia (https://www.mindefensa.gov.co/irj/portal/Mindefensa/contenido?NavigationTarget=navurl://c17680c4c6ae25daaa589817c6ce4205 ) en donde cada uno de estos viene en archivos independientes, los cuáles fueron consolidados y se extraen los campos necesarios para cada variable.
Adicionalmente se descargó de la página web del Dane (https://geoportal.dane.gov.co/geovisores/territorio/consulta-divipola-division-politico-administrativa-de-colombia/) las coordenadas para geolocalización de los municipios.
Se cuentan con las siguientes variables y para cada uno de estas se realizó el proceso de extracción de las columnas de interés, así como el filtro del periodo de análisis, el cual va de 2017 al 2022:
DELITOS_CONTRA_MEDIO_AMBIENTE, DELITOS_INFORMATICOS, DELITOS_SEXUALES, EXTORSION, HOMICIDIO, HOMICIDIO_ACCIDENTE_TRANSITO, HOMICIDIO_COLECTIVO_VICTIMAS, HURTO_COMERCIO,HURTO_PERSONAS2017-2023, HURTO_RESIDENCIAS,HURTO_VEHICULOS, LESIONES_ACCIDENTES_TRANSITO, LESIONES_PERSONALES, SECUESTRO, VIOLENCIA_INTRAFAMILIAR.

## Resultados Preliminares

#### Gráfico de barras por año
<img src="./Resultados%20Preliminares/Grafico%20de%20barras%20por%20año.png" alt="Grafico de barras por añon" width="300" height="200">

#### Grafico de barras por delito
<img src="./Resultados%20Preliminares/Grafico%20de%20barras%20por%20delito.png" alt="Grafico de barras por delito" width="300" height="200">

Se observa que de los últimos 6 años , el año 2020 fué el que presento menor cantidad de delitos (731.361) esto puede ser efectos de la pandemia de COVID en donde la mayoria de personas se encontraban en cuarentena la mayor parte del año, adicionalmente 2018 ha sdo el mes con mayor cantidad de delitos (790.434), sin embargo en los último 3 años del análisis se evidencia un crecimiento añoa a año.

El hurto a personas es el delito que ha afectado en gran medida a la población en los últimos años siendo la categoría con mayor participación 1.619.489, seguido de lesiiones personales con 680.670 casos.

#### Latitud y longitud
<img src="./Resultados%20Preliminares/Latitud%20y%20Longitud.png" alt="Latitud y longitud" width="300" height="200">

Luego de realizar el análisis de clustering con k-means sin utilizar componentes principales para reducir la dimensionalidad, para tener una primera vista con los datos de entrada, se puede observar que sugiere dos clusters gracias al coeficiente de silueta con un valor de 0.98.

## Documento de la Entrega

...

</body>
</html>



