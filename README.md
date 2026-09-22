## En conjunto con una base de datos suministrada por MEData (el portal de datos públicos del Distrito de Medellín). Se toman registros de incidentes de tránsito desde los años 2014 a 2020. Con el onjetivo de alocar recursos en la ciudad para prevenir potenciales incidentes nuevos.

## Para entender correctamente las necesidades de la entidad de tránsito se debe primero analizar el tamaño de la base de datos. Se observan más de 280 mil registros de incidentes junto con diferentes características en el dataset.

# Descripción del dataset:
'NRO_RADICADO' = Número de identificación del accidente ocurrido (identificador único)
“Latitud” = Coordenada de latitud 
“Longitud” = Coordenada de longitud 
“CLASE_ACCIDENTE” = Clase o tipo de accidente ocurrido
“DIRECCION” = Nomenclatura de la calle (TODAS ELLAS SON DE MEDELLÍN) 
"CBML" = En Colombia, concretamente en el contexto urbanístico y catastral del departamento de Antioquia, CBML es un código alfanumérico que significa: Municipio, Barrio, Manzana y Parcela.
"Gravedad Incidente" = gravedad del accidente
"nombre comuna" = nombre del municipio
"Barrio" = barrio
"Diseño" = tipo de vía en la que se produjo el accidente
"Año" = año del accidente
"FECHA_ACCIDENTE" = fecha del accidente
"HORA_ACCIDENTE" = hora del accidente
"codigo comuna" = código de la comuna
"Comuna" = comuna

## Se hacen varias exploraciones de datos y se visualizan tales hallazgos, se identifican datos atípicos ('outliers') y se procede con la limpieza del dataset. 

## Posteriormente se usan los datos para implementar 3 modelos de Machine Learning de clusterización: K-Means, DBSCAN y Clustering Jerárquico (HC). 

## Una vez entrenados y ejecutados los modelos, comparamos los hallazgos para así elegir un modelo óptimo y escalable para satisfacer las necesidades requeridas por la entidad estatal. 

# Lo que se me solicita que contenga el informe final:
1. Dónde ubicar:
*   los agentes de tránsito
*   las ambulancias
2. Los horarios y el personal qué debe estar disponible para atender los eventos. Teniendo en cuenta en qué horarios, días y fechas particulares se presentan mayor accidentalidad y de qué tipo.
3. Se espera que tenga en cuenta los años y la estacionalidad al momento de analizar la accidentalidad.
4. Recomendaciones para prevenir los accidentes de tránsito.

# A lo largo del notebook se pueden encontrar varias celdas de texto Mark Down donde se deja un análisis en diferentes índices del script. Al igual que el informe ejecutivo final solicitado.
