# Sistema-de-alertas-s-smicas---Proyecto-Grupal-DTS04
Projecto grupal


## **Contexto**

Los desastres naturales pueden resultar en un gran número de muertes, pérdida de propiedades, y daños irreparables. Es por esto que la predicción temprana y medidas de protección y atención apropiadas resultan urgentes.

Particularmente, los sismos, son el fenómeno natural del cual tenemos menor capacidad predictiva 

## **Propuesta de trabajo**

Para este proyecto ustedes harán parte del equipo de atención de desastres del país latinoamericano de su preferencia. En este momento se encuentran trabajando en un proyecto tri-nacional en conjunto con el Estados unidos (USGS) y Japón (JMA) llamado “Working towards global standardization of seismological networks and effective communication to the civilian community. ” 

Los objetivos de esta alianza son:

<h4>1. Crear una  base de datos depurada que contemple los datos de las tres naciones de forma estandarizada:</h4>

A las autoridades les interesa tener la información estándar de todos los países para poder crear un mecanismo de clasificación. La definición de un evento sísmico y los criterios de alerta adecuados deben tener en cuenta la calidad de los datos.


<h4>2. Implementar mecanismos de comunicación y alerta a la comunidad civil en un lenguaje intuitivamente interpretable a través de Internet o cellBroadCast:</h4>


## ¿Como lo hacemos?  

### Enfoque 1 [Data Analysis focus]

Analizando profundamente la relacion de los sismos con otra u otras particularidades de su pais latinoamericano escogido.

Ejemplos de lineas de investigacion (Solo para que se inspiren. Pueden divagar y escoger lo que se les ocurra, su mente es el limite!):

- Sismicidad secundaria (después de un gran sismo) ¿cómo afecta? ¿Qué ha pasado? Se pueden anticipar medidas si es que hay algo sistemáticamente mal?
- Es aconsejable que haya una reubicación de habitantes en zonas como CDMX que es sabido esta construida en una zona geológicamente inestable y con alta actividad sísmica?
- Derribando (o acentuando) mitos: Tiene que ver el clima con la propensión a sismos de mayor “magnitud” y los cambios estacionales?
- Efectos secundarios no deseables: Sismos y Tsunamis, Problemas en redes eléctricas, incendios…


Entregables tangibles minimos:
Mapa de geolocalizacion de los sismos escogidos que contemple la actualizacion cada hora. 
La informacion que debe tener DEBE ser la escogida en su analisis. NO debe ir informacion cientifica como: Magnitud, Profundidad si esta no esta explicada o se indica por que es relevante.


### Enfoque 2 [Machine Learning Focus]

Aplicar un modelo de clasificacion no supervisada. 
La idea aqui NO sera predecir un sismo, sino, dadas las caracteristicas que tienen los sismos, clasificarlos segun patrones como Peligrosidad Media/Alta/Baja
o cualquier enfoque que quieran aplicar. 

Entregables tangibles minimos:
Presentacion de las etiquetas de clasificacion y performancia del modelo.  
Deploy del modelo de ML - puesta en produccion (plataforma a elección)

## **Datasets y fuentes complementarias**

Fuentes de datos obligatorias:
+ Estados Unidos https://earthquake.usgs.gov/fdsnws/event/1/
+ Japon https://www.fdsn.org/networks/detail/JP/
+ Observatorio Latinoamericano de su preferencia ***********

Nota: El producto final debe tener en su etapa de *extraccion* los datos en formato JSON o GeoJSON. Formatos de texto como CSV podrian usarse en los pasos intermedios para hacer sus test respectivos de ser necesario, pero no seran admitidos en la entrega final.

## USGS 
### Diccionario:
https://earthquake.usgs.gov/data/comcat/index.php#tsunami
### Documentación de API:
https://earthquake.usgs.gov/fdsnws/event/1/
### Rango de fechas/formatos disponibles por catálogo
https://earthquake.usgs.gov/data/comcat/catalog/us/
### FDSN	Web	Service	Specifications
http://www.fdsn.org/webservices/FDSN-WS-Specifications-1.0.pdf


# Semana 1:

* Oscar: Busqueda de información relacionada con sismos en paises latinoamericános, presentación de sismos y establecimiento de repositorio comunal.
Puedes ver este commit?
* Lala (después lo cambio XD): Busqueda de información relacionada con sismos en Japón. Acá hago mi segundo cambio.
* Gise: Conectar a postgres y docker


# Tareas.

[objetivos semanales y tareas integrantes](https://www.google.com/search?client=opera&q=proyecto&sourceid=opera&ie=UTF-8&oe=UTF-8)
