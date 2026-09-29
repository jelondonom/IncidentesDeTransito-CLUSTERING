## In conjunction with a database provided by MEData (the public data portal of the District of Medellín), traffic incident records from 2014 to 2020 are used. The objective is to allocate resources throughout the city to prevent potential new incidents.

## To properly understand the needs of the traffic authority, the size of the database must first be analyzed. More than 280,000 incident records are observed, along with different characteristics in the dataset.

# Dataset Description:

'NRO_RADICADO' = Identification number of the accident that occurred (unique identifier)
“Latitud” = Latitude coordinate
“Longitud” = Longitude coordinate
“CLASE_ACCIDENTE” = Class or type of accident that occurred
“DIRECCION” = Street address nomenclature (ALL OF THEM ARE IN MEDELLÍN)
"CBML" = In Colombia, specifically in the urban and cadastral context of the department of Antioquia, CBML is an alphanumeric code that stands for: Municipality, Neighborhood, Block, and Parcel.
"Gravedad Incidente" = Accident severity
"nombre comuna" = Municipality name
"Barrio" = Neighborhood
"Diseño" = Type of road where the accident occurred
"Año" = Year of the accident
"FECHA_ACCIDENTE" = Date of the accident
"HORA_ACCIDENTE" = Time of the accident
"codigo comuna" = Commune code
"Comuna" = Commune

## Several data explorations are conducted and the findings are visualized. Outliers are identified, and the dataset is subsequently cleaned.

## The data is then used to implement 3 Machine Learning clustering models: K-Means, DBSCAN, and Hierarchical Clustering (HC).

## Once the models have been trained and executed, we compare the findings in order to select an optimal and scalable model to meet the requirements of the government entity.

# What the final report is required to contain:

1. Where to locate:

* traffic officers
* ambulances

2. The schedules and personnel that should be available to respond to events. Taking into account the times, days, and specific dates when higher accident rates occur, as well as the type of accidents.
3. The analysis is expected to take into account the years and seasonality when analyzing traffic accidents.
4. Recommendations to prevent traffic accidents.

# Throughout the notebook, several Markdown text cells can be found containing analyses at different points of the script, as well as the requested final executive report.
