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

Para el desarrollo de nuestro proyecto se descargaron las fuentes de delitos desde la página web del Ministerio de Defensa Nacional de Colombia (https://www.mindefensa.gov.co/irj/portal/Mindefensa/contenido?NavigationTarget=navurl://c17680c4c6ae25daaa589817c6ce4205 ) en donde cada uno de estos viene en archivos independientes los cuáles se consolidados y se extraen los campos necesarios para cada variable.
Adicionalmente se descargó de la página web del Dane (https://geoportal.dane.gov.co/geovisores/territorio/consulta-divipola-division-politico-administrativa-de-colombia/) con las coordenadas para geolocalización de los municipios.
Se cuentan con las siguientes variables y para cada uno de estas se realizó el proceso de extracción de las columnas de interés, así como el filtro del periodo de análisis el cuál va de 2017 al 2022:
DELITOS_CONTRA_MEDIO_AMBIENTE, DELITOS_INFORMATICOS, DELITOS_SEXUALES, EXTORSION, HOMICIDIO, HOMICIDIO_ACCIDENTE_TRANSITO, HOMICIDIO_COLECTIVO_VICTIMAS, HURTO_COMERCIO,HURTO_PERSONAS2017-2023, HURTO_RESIDENCIAS,HURTO_VEHICULOS, LESIONES_ACCIDENTES_TRANSITO, LESIONES_PERSONALES, SECUESTRO, VIOLENCIA_INTRAFAMILIAR.

## Resultados Preliminares

#### Gráfico de barras por año
![Grafico de barras por año](./Resultados%20Preliminares/Grafico%20de%20barras%20por%20año.png)

#### Grafico de barras por delito
![Grafico de barras por delito](./Resultados%20Preliminares/Grafico%20de%20barras%20por%20delito.png)

#### Evolución por delito
![Evolucion por delito](./Resultados%20Preliminares/Evolucion%20por%20delito%20ultimos%206%20años.png)

#### Matriz de correlación
![Matriz de Correlacion](./Resultados%20Preliminares/Matriz%20de%20correlación.png)

#### Delitos en Colombia
![Delitos en Colombia](./Resultados%20Preliminares/Delitos%20en%20Colombia.png)

#### Latitud y longitud
![latitud y longitud](./Resultados%20Preliminares/Latitud%20y%20Longitud.png)

## Documento de la Entrega

...

</body>
</html>



