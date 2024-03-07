# **HENRY PROYECTO FINAL** 
![Henry Imagen](https://github.com/LeandroHerner/Proyecto_Final/blob/main/imagenes/HEADER-BLOG-NEGRO-01.jpg)

### MODALIDAD GRUPAL

*COHORTE PART TIME 05* <br>
*GRUPO* 6<br>

**INTEGRANTES:**<br>
    - LEANDRO HERNER<br>
    - LUCAS RAÑA<br>
    - HORACIO MORAZZO<br>
    - FEDERICO NAPOLITANO<br>
    - NICOLAS GUTIERREZ COLL<br>


## INTRODUCCION
Desde la academia de Henry para el Bootcamp de Data Science, nos han encargado generar un proyecto final en donde nos ponemos en el papel profesional de Data Scientis. Abarcando un proyecto global en equipo de 5 personas, tenemos que brindarle una solución final en donde abarcaremos todos los temas aprendidos hasta la fecha.

Para esto, el grupo se ah puesto en el papel de una empresa consultora de Data, llamada "INSIGHT NOVA". 


## CONTEXO DEL PROYECTO
![Taxis Amarillos](https://github.com/LeandroHerner/Proyecto_Final/blob/main/imagenes/1572460700191.jpg)
Dada la alta contaminación de CO2, el calentamiento global y el aumento de vechiculos empleados para el transporte de pasajeros la ciudad de Nueva York, ah establecido que para el año 2030, todos los vehiculos de transportes de pasajeros sean eléctricos. 
De esta forma la Ciudad de NY luchara y buscara generar una reducción de CO2.
Con las tecnologias actuales, esta alta frecuencia de movimientos tambien genero una gran capacidad de recopilar datos y almacenarlos para luego poder ser analizados. Gracias a esto, la ciudad ofrece en su web información muy valiosa.

Gracias a este panorama y la información dispoible desde la ciudad de NY, una empresa de transporte se comunica con "INSIGHT NOVA" para poder realizar un proyecto en el cual, analizando esta información se les pueda brindar respuestas de valor y de esta forma generar una optimización en sus operaciones y decisiones.


# OBJETIVO
Encontrar la mejor forma de optimizar los viajes de los vehiculos para obtener más ganancias y de esta forma lograr la mejor trancisión posible de autos de combustion a eléctricos solicitada por la ciuada de NY. 


# PROPUESTA
El equipo de "INSIGHT NOVA" tomara los datos de la web proporcioandos por la ciudad de NY, para generar un análisis de sus datos y poder obtener información valiosa para la empresa.
Para esto, se generara un sistema en el cual cargaremos toda la informacion en Google Cloud, pasara por un proceso de reducción y ETL para tener disponible información limpia y segura a la hora de analizar.
Para generar todo este proceso se utiliza un stack tecnológico en el cual abarcamos muchas herramientas que permiten el procesamiento y la gestión de grandes volumenes de datos.


## EQUIPO Y ROLES
El equipo esta formado por 5 Data Science, en el cual se destinan roles principales entre los integrantes para una mejora de optimización de tiempos y recursos.
Roles ejercidos para el proyecto:

### Data Engineer
Encargado de generar la ingenieria de datos, generan el diseño y la infraestructura de los mismos, para luego pasar a la recopilación, procesamientos, limpieza y almacenamiento de los datos de forma correcta y limpia para dejar disponible los datasets al los analistas de datos y al encargado de generar el modelo de ML.

Personas encargadas:<br>
- Leandro Herner
- Nicolás Gutierrez Coll

### Data Analyst
Este perfil van a ser los encargados de realizar la lectura final de los datos para encontrar información valiosa y determinante para el negocio.
El resultado de estos análisis la plasmaran en tableros dinamicos para obtener una lectura rapida y precisa. Gracias a esto, con una rapida mirada a los graficos y a los KPIs se podra generar datos determinantes a la hora de la toma de decisiones.<br>

Personas encargadas:<br>
- Horacio Morazzo
- Federico Napolitano

### Machine Learning
Este área se encarga de generar un modelo de aprendizaje automatico, en el cual con los datos de entrada existentes tiene la capacidad de predecir datos a futuro con la inteligencia artificial. <br>
Gracias a esto, se logran obtener una predición de datos futura con un nivel de confianza aceptable. Gracias a este modelo, brindaremos información para adelantarnos a hechos y poder tener una ventaja competitiva a la hora de tomar decisiones.

Personas encargadas:<br>
- Lucas Raña

<br>

# METODOLOGIA DE TRABAJO

A continuación, detallaremos el metodo de trabajo propuesto por el equipo de trabajo de "INSIGHT NOVA".

Dentro de Google Cloud, en la maquina virtual.

Se generar un WebScraping para obtener todos los data sets necesarios. Los de taxis amarillos y de Uber esta en la pagina de la ciudad de NY:
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Y se toman datos del clima de la siguente API:
https://open-meteo.com/en/docs/historical-weather-api

Una vez obtenidos y almacenados los datasets se pasan por un proceso de reducción al 5%, limpieza y transformación para dejarlo en condiciones de ser usado en su posterioridad.

Se generan tablas a pedido para el sector de Data Analyst y Machine Learning.

Estos datasets y las tablas se dejan cargadas en Big Query para ser tomadas por las otras plataformas dentro de GCP.

De esta forma, el sector de Data Analytics y Machine Learning generan los tableros visuales y el modelo predictivo para presentar al cliente la información limpia, analizada y valiosa para tomar decisiones.

<br>

# KPIS PROPUESTOS
Para el proyecto solicitado se idealizaron una serie de KPIs, para poder obtener rapidamente información del negocio leyendo indicadores acordes al modelo de negocio.

Estos son los KPIs establecidos: <br>
    
    - KPI 1: Incrementar la cantidad de viajes realizados por turno de trabajo (8hs) en un 5% mensual durante el primer semestre. <br>
    - KPI 2: Incrementar el promedio mensual de la tarifa cobrada por viaje de cada vehiculo por milla recorrida en un 7% mensual durante el primer trimestre. <br>
    - KPI 3: Reducir costos operativos de la flota en un 5% anual hasta el 2030. <br>
    - KPI 4: Mantener inversion como porcentaje de ganancias mensuales por debajo del 30% hasta 2032. <br>
    - KPI 5: Reducir emisión en un 20% anual hasta 2030 para llegar a emision 0 en ese año. <br>

<br>

# HERRAMIENTAS UTILIZADAS

### Python
Principal herramienta de programación utilizada como base y como apoyo. El gran poder de ejecución que tiene python nos ayudara a trabajar los datasets y a realizar ejecuciones dentro de google cloud.

### Google Cloud

Servicio general de google que brinda dentro de su propia plataforma además de almacenamiento, una serie de herramientas que serán de mucha ayuda a la hora de gestionar proyectos de Bussines Inteligent. <br>
Las herramientas utilizadas dentro de esta plataforma son: <br>

    - Google computer Engine: Maquina Virtual, que nos permitira generar la carga incremental.
    - Cloud Storage: Almacenamiento estilo Data Lake.
    - Big Query: Almacenamiento estilo Data Warehouse.
    - Google Scheduler: Calendario para ejecuciones programadas.
    - Vertex AI: Módulo de aprendizaje supervisado para la realización de Machine Learning.
    - Looker: Módulo para la realización del tablero.

### Render

Render es una plataforma en la nube que ofrece una variedad de servicios para ayudar a los desarrolladores a crear, implementar y escalar aplicaciones web. Para este proyecto utilizamos Render para poder disponibilizar la API con el modelo de machine learning sobre la predicción en el horario que se realiza la consulta de la demanda en el distrito ingresado

[Modelo disponibilizado](https://proyecto-final-z9ia.onrender.com/docs)