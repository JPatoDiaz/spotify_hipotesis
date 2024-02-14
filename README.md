# Validación de hipótesis de éxito para el lanzamiento de un nuevo artista con data de Spotify y otras plataformas. 

## Contexto

En un mundo en el que la industria musical es extremadamente competitiva y está en permanente evolución, la capacidad de tomar decisiones basadas en datos se ha convertido en un activo invaluable.

En este contexto, una discográfica se enfrenta al emocionante desafío de lanzar un nuevo artista en el escenario musical global y busca a través de data de Spotify trazar el camino al éxito buscando validar las siguientes hipótesis: 

-   Las canciones con un mayor BPM (Beats Por Minuto) tienen más éxito en términos de cantidad de streams en Spotify.
-   Las canciones más populares en el ranking de Spotify también tienen un comportamiento similar en otras plataformas como Deezer.
-   La presencia de una canción en un mayor número de playlists se relaciona con un mayor número de streams.
-   Los artistas con un mayor número de canciones en Spotify tienen más streams totales.
-   Las características de la música influyen en el éxito en términos de cantidad de streams en Spotify.

## ¿Cuál fue el objetivo? 

Analizar las canciones más escuchadas en el 2023 en la plataforma Spotify y su comportamiento en otras plataformas como Dezeer y  Apple Music para validar las siguientes hipótesis: 

-   Las canciones con un mayor BPM (Beats Por Minuto) tienen más éxito en términos de cantidad de streams en Spotify.
-   Las canciones más populares en el ranking de Spotify también tienen un comportamiento similar en otras plataformas como Deezer.
-   La presencia de una canción en un mayor número de playlists se relaciona con un mayor número de streams.
-   Los artistas con un mayor número de canciones en Spotify tienen más streams totales.
-   Las características de la música influyen en el éxito en términos de cantidad de streams en Spotify.


## ¿Qué insumos/herramientas usamos para el análisis?  

### Insumos
- Set de datos con la información de las canciones más escuchadas durante el 2023 en Spotify 
- Set de datos con información del comportamiento de estás canciones en otras plataformas 
- Set de datos la información técnica de cada una de las canciones

### Herramientas

- BigQuery
- PowerBI
- GoogleColab

### Lenguajes

- SQL
- Phyton

## ¿Cuál fue el proceso de trabajo?  

El desarrollo del proyecto se llevo a través de las siguientes fases

-   Procesar y preparar los datos con consultas en SQL 
-   Hacer un análisis exploratorio (AED).
-   Aplicar técnicas de análisis cómo:
    - Segmentación de categorías
    - Correlación de variables 
    - Prueba de significancia a través del test de Wilcoxon
    - Regresión lineal
-   Construcción de dashboard.
-   Presentación de resultados con stakeholders.
