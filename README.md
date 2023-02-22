# Vuelos-demorados---coderhouse

Introduccion:

OBJETIVO:

Se busca reducir los retrasos y cancelaciones de los vuelos en distintas aerolineas de un determinado pais.

CONTEXTO EMPRESARIAL:

Periodicamente salen y llegan vuelos a distintos aeropuertos, pero muchos de ellos encuentran diferentes situaciones que provocan un retraso en lo planificado y perjudicando asi a los clientes y retrasando tambien otros vuelos.

PROBLEMA COMERCIAL:

Muchas veces el clima, la seguridad, las inspecciones de las aeronaves provocan retrasos o incluso cancelaciones en los vuelos programados, costandole a la aerolinea muchisimo dinero, perdida de clientes, etc.

Acudieron a nosotros, los socios del aeropuerto ubicado en cierta ciudad, expresando sus problematicas y buscando soluciones, por los que se propuso crear un algoritmo capas de predecir estos retrasos o cancelaciones por medio de un entrenamiento a base de los registros en sus bases de datos.

CONTEXTO ANALITICO:

Se nos ha facilitado una registro que contiene una gran cantidad de datos de vuelos, aeronaves, clientes, condiciones climaticas en esa ubicacion y en determinados momentos, cantidad de vuelos por aerolinea y el registro que mas nos importa... si fue retrasado o no.

Este archivo es de tipo (csv) separado por comas y contiene mas de 400.000 registros y 30 columnas.

EDA:

Se describen las tareas a realizar en esta parte del proyecto.

1- Extraer el archivo y verificar su lectura

2- Leer y crear visualizaciones para saber como esta compuesto dicho archivo

3- Realizar un analisis exploratorio de los datos, buscar patrones que nos puedan proveer mas informacion y proyectarlos como visualizaciones.

El cliente tiene un conjunto de preguntas, las cuales es fundamental encontrar una respuesta.

¿Hay relacion entre los meses y la cantidad de vuelos cancelados?

¿Tienen que ver las epocas de turismo?

¿Hay aerolineas que tienen mas vuelos cancelados que otras?

¿Hay relacion entre el clima y las demoras?

Descripcion de las variables
MONTH: Month
DAY_OF_WEEK: Day of Week
DEP_DEL15: TARGET Binary of a departure delay over 15 minutes (1 is yes)
DISTANCE_GROUP: Distance group to be flown by departing aircraft
DEP_BLOCK: Departure block
SEGMENT_NUMBER: The segment that this tail number is on for the day
CONCURRENT_FLIGHTS: Concurrent flights leaving from the airport in the same departure block
NUMBER_OF_SEATS: Number of seats on the aircraft
CARRIER_NAME: Carrier
AIRPORT_FLIGHTS_MONTH: Avg Airport Flights per Month
AIRLINE_FLIGHTS_MONTH: Avg Airline Flights per Month
AIRLINE_AIRPORT_FLIGHTS_MONTH: Avg Flights per month for Airline AND Airport
AVG_MONTHLY_PASS_AIRPORT: Avg Passengers for the departing airport for the month
AVG_MONTHLY_PASS_AIRLINE: Avg Passengers for airline for month
FLT_ATTENDANTS_PER_PASS: Flight attendants per passenger for airline
GROUND_SERV_PER_PASS: Ground service employees (service desk) per passenger for airline
PLANE_AGE: Age of departing aircraft
DEPARTING_AIRPORT: Departing Airport
LATITUDE: Latitude of departing airport
LONGITUDE: Longitude of departing airport
PREVIOUS_AIRPORT: Previous airport that aircraft departed from
PRCP: Inches of precipitation for day
SNOW: Inches of snowfall for day
SNWD: Inches of snow on ground for day
TMAX: Max temperature for day
AWND: Max wind speed for day
