 Código markdown
# Creación de un programa para que a partir de un archivo shapefile muestre la ubicaciion de los baches y muestre los poligonos de ellos
**Autores:** Iram Antonio Mendez Partida, Sergio Mejia Manso

## Introducción
La calidad de las infraestructuras viales es un factor clave para el desarrollo económico, social y ambiental de cualquier región. En particular, los baches en las carreteras representan un problema significativo que afecta tanto a la seguridad de los ciudadanos como a la eficiencia del transporte. En el caso específico de la carretera Colima-Coquimatlán, especialmente a la altura del km 2.5, la presencia de baches ha generado consecuencias negativas no solo para los conductores, sino también para la actividad económica local, especialmente en el sector transportista. Estos baches, además de generar daños a los vehículos y aumentar los costos de mantenimiento, contribuyen a un mayor riesgo de accidentes y reducen la competitividad económica de la región.

Esta investigación se enfoca en la optimización del proceso de llenado de baches, buscando mejorar la durabilidad de las reparaciones y reducir el desperdicio de materiales. Al lograr una reparación más eficiente y duradera, se busca disminuir los costos asociados con el mantenimiento vial y garantizar un flujo económico más estable y seguro. Además, se pretende contribuir a la mejora de la calidad de vida de los ciudadanos que transitan por esta carretera, reduciendo los riesgos de accidentes y daños vehiculares, y apoyando la actividad económica de la región, especialmente en el transporte de mercancías.

En este contexto, es esencial comprender los factores geográficos y ambientales que influyen en la formación de los baches. La carretera Colima-Coquimatlán atraviesa una región con suelos predominantemente sedimentarios y arcillosos-arenosos, que, debido a sus características de retención de agua y ciclos de expansión y contracción, facilitan la aparición de grietas en el pavimento. Estos baches se ven exacerbados por el tráfico pesado de camiones, la falta de mantenimiento adecuado y la mala calidad de los materiales utilizados en las reparaciones anteriores.

## Desarrollo
El objetivo de este estudio es optimizar el proceso de llenado de baches en la carretera Colima-Coquimatlán, específicamente a la altura del km 2.5, para reducir el impacto económico, social y ambiental generado por los baches. A continuación, se describe el desarrollo experimental que se realizó para abordar esta problemática, desde la caracterización de los baches hasta el cálculo preciso del material necesario para su reparación.

1. Identificación y Caracterización de los Baches
El primer paso en este proceso fue la identificación y caracterización de los baches presentes en la carretera Colima-Coquimatlán. Para ello, se realizó un recorrido en la carretera con la colaboración de ingenieros civiles y personal especializado en mantenimiento vial. Se identificaron un total de 30 baches distribuidos a lo largo de los primeros 5 kilómetros de la carretera, de los cuales 15 fueron seleccionados para el análisis detallado debido a su tamaño y relevancia en términos de impacto en el tráfico.

Durante la caracterización de los baches, se registraron las siguientes variables para cada uno de ellos:

Dimensiones del bache (longitud, ancho y profundidad) mediante el uso de cintas métricas y mediciones de profundidad.
Forma del bache: Se observó que la mayoría de los baches presentaban una forma irregular, lo que dificultaba su cálculo con fórmulas geométricas simples.
Condiciones del pavimento: Se analizó el estado de la capa asfáltica, observando grietas, hundimientos y fisuras.
Además, se registraron las condiciones meteorológicas de la región, dado que la formación de los baches está influenciada por la cantidad de precipitaciones y el tipo de suelo en el área.

2. Análisis de los Materiales del Suelo
Como se mencionó previamente, los suelos en la región de Coquimatlán son predominantemente arcillosos-arenosos, con una gran capacidad de retención de agua. Se realizaron estudios preliminares para determinar las propiedades del suelo en la zona afectada por los baches. Esto incluyó pruebas de:

Granulometría: Para determinar la proporción de arena, limo y arcilla en los suelos.
Permeabilidad: Para analizar la capacidad del suelo para permitir el paso de agua, un factor clave en la formación de baches.
Expansividad: Mediante la medición de la hinchazón y contracción de los suelos, se pudo confirmar que los suelos en la zona tienen una alta capacidad de expansión y contracción, lo que contribuye a la aparición y crecimiento de grietas en el pavimento.
Los resultados de estas pruebas fueron clave para determinar el tipo de material adecuado para el relleno de los baches, asegurando que se usara un material que pudiera resistir la presión de los vehículos y las condiciones climáticas de la región.

3. Aplicación del Cálculo Integral para Determinar el Volumen de los Baches
Dado que los baches no tienen una forma regular, se optó por utilizar el cálculo integral para estimar el volumen de cada uno de los baches de manera precisa. Para ello, se utilizó el siguiente procedimiento:

Modelado de la forma del bache: Cada bache fue modelado como una curva en un sistema de coordenadas cartesianas, teniendo en cuenta sus dimensiones irregulares (longitud, ancho y profundidad).

Función matemática para la curva: Se supuso que la forma del bache podía aproximarse a una función matemática continua, que describiera su perfil en función de la longitud y la profundidad. La ecuación de esta función fue determinada mediante el uso de métodos de ajuste de curvas a partir de las mediciones de campo.

Cálculo integral: Con la ecuación de la curva establecida, se procedió a calcular el área bajo la curva utilizando el cálculo integral. La fórmula básica utilizada fue:

                            
               
![formula basica](https://github.com/user-attachments/assets/4f6af199-97f0-4c35-b341-44237e1ef41e)




Donde f(x) es es la función que describe el perfil del bache,  a y b son los límites de la longitud del bache.
Estimación del material necesario: Una vez calculado el volumen del bache, se estimó la cantidad de material necesario para su relleno. Para esto, se usó el material asfáltico de alta calidad con características adecuadas para resistir las condiciones climáticas y el tráfico pesado en la zona.

4. Selección y Preparación del Material de Relleno
La elección del material de relleno fue fundamental para garantizar la durabilidad y la eficacia de las reparaciones. El material seleccionado fue una mezcla de asfalto modificado con polímeros, que ofrece una mayor resistencia y flexibilidad en comparación con el asfalto convencional.

Se calculó la cantidad de material necesario para rellenar cada uno de los baches en función de su volumen estimado. Además, se implementaron técnicas de compactación para asegurar que el material se asiente de manera eficiente y evite el hundimiento posterior. Durante este proceso, se tuvo en cuenta la temperatura ambiente, ya que el asfalto debe ser trabajado a temperaturas específicas para obtener el mejor rendimiento.

5. Procedimiento de Reparación
El procedimiento de reparación consistió en los siguientes pasos:

Limpieza del bache: Se retiró todo el material suelto o deteriorado en el área del bache, asegurando que la superficie estuviera limpia para una mejor adherencia del material de relleno.
Aplicación del material de relleno: Se colocó el asfalto modificado en el bache, distribuyéndolo de manera uniforme según el volumen calculado mediante el cálculo integral.
Compactación: El material de relleno se compactó utilizando maquinaria especializada para garantizar que no quedaran huecos o espacios vacíos en el interior del bache.
Revisión y evaluación: Finalmente, se revisó la calidad de la reparación, asegurando que el nivel de la carretera fuera homogéneo y no existieran irregularidades.
6. Evaluación del Impacto
Una vez realizadas las reparaciones, se llevó a cabo un monitoreo de las condiciones del pavimento en los baches reparados. Se realizaron visitas periódicas para evaluar la durabilidad de las reparaciones, observando su resistencia al tráfico pesado y a las condiciones climáticas. Además, se registraron los costos de mantenimiento antes y después de la intervención para medir el impacto económico.
Manejo de datos
La formula general para el calculo de volumen de un bache es:


![Formula general](https://github.com/user-attachments/assets/ac06661d-c906-48ee-963b-52dd16c395d2)

              


Ejemplo:

![eje-1](https://github.com/user-attachments/assets/f4247754-11d8-4618-aa57-e1083af63916)

![eje-2](https://github.com/user-attachments/assets/f220257b-49b5-477d-9b26-0cb9ca01835b)

![eje-3](https://github.com/user-attachments/assets/76289281-2d82-46bd-b309-bc1e1f8a95fb)

![eje-4](https://github.com/user-attachments/assets/7b286a99-59ef-4aeb-933a-18385384f234)






 
A partir de los resultados obtenidos podemos considerar cual es la relación entre el cálculo con la severidad del bache, mientras más área sobre la curva haya, mayor será el bache.
Necesitaremos tomar medidas al bache (largo, ancho y profundidad) y esto se podría convertir en algo riesgoso de hacer ya que los baches analizados en cuestión se encuentran a la altura del km. 2.5 de la carretera Colima-Coquimatlán. Una solución a esta problemática seria que las personas encargadas de medir el bache lo hagan con el mayor cuidado posible, como poner conos, señales reflectantes y usar ropa adecuada para ser visto desde distancias alejadas.


## Manejo de Datos

Codigo para mostrar la ubicacion y poligono de los baches:

from google.colab import drive
drive.mount('/content/drive')
%cd /content/drive/MyDrive/Programacion II/Proyecto
import geopandas as gpd
import folium
from shapely.geometry import Point

shp_path = "/content/drive/MyDrive/Programacion II/Proyecto/Bache.shp"
gdf = gpd.read_file(shp_path)
Verificar el CRS original
print(f"CRS original: {gdf.crs}")
 
if gdf.crs is None:
    gdf.crs = "EPSG:6367"

gdf = gdf.to_crs(epsg=4326)

radius_in_degrees = 0.00002 # Aproximadamente 5.5 metros
gdf['geometry'] = gdf.geometry.apply(lambda geom: geom.buffer(radius_in_degrees))

centroide = gdf.unary_union.centroid
mapa = folium.Map(location=[centroide.y, centroide.x], zoom_start=15)

for _, row in gdf.iterrows():
    folium.GeoJson(
        row.geometry,
        style_function=lambda x: {
            "fillColor": "blue",
            "color": "black",
            "weight": 1,
            "fillOpacity": 0.6,
        },
        tooltip="Polígono del Bache"
    ).add_to(mapa)

from IPython.display import display
display(mapa)

Codigo visto desde google colab:
![Correccion 1](https://github.com/user-attachments/assets/1ac156fc-b3b6-4c54-8418-282dc807b085)




![Correccion 2](https://github.com/user-attachments/assets/e0d163a6-585b-4fb4-98a1-352a838ec79a)




![Correccion 3](https://github.com/user-attachments/assets/81630428-498f-4845-a702-670569749f52)


El objetivo de este codigo es cargar un archivo de shapefile (SHP) que contiene información sobre la ubicación de baches, crear polígonos circulares representando cada bache, y visualizarlos en un mapa interactivo utilizando GeoPandas, Shapely y Folium en Google Colab. 
El codigo Conecta Google Drive a Google Colab para acceder a shapefile, posteriormente se importan las librerias de geopandas, follium y shapely.geometry ya que nos basaremos en estas librerias para poder trabajar.

Una vez que cargas la libreria lo primero que hacemos es cargar el archivo shp, se verifica el sistema de coordenadas ya que si no esta el archivo shp en EPSG:4326 las coordenadas de los baches se mostraran en algun lugar que no sea tu ubicacion deseada.

Algo verdaderamente funcional que decidi implementar en mi codigo es que si tu archivo shp no esta en el sistema de coordenadas EPSG:4326 con el comando "gdf = gdf.to_crs(epsg=4326)" puedes transformar tu sistema de coordenadas a al deseada.

Despues de haber hecho todos estos pasos creamos un poligono circular para representar los baches, posterior a eso calculamos el punto central de todas las geometrias y creamos el mapa y agregamos los poligonos al mapa.


## Resultados
A partir de este análisis, podemos concluir que el uso del cálculo integral para determinar el volumen de los baches proporciona una herramienta matemática eficaz para optimizar la reparación de infraestructuras viales. Sin embargo, es importante tener en cuenta los riesgos inherentes a la medición directa en la carretera, por lo que se deben tomar medidas de seguridad adecuadas.
La relación entre la severidad del bache y el área bajo la curva demuestra que, cuanto mayor sea el volumen calculado, mayor será el impacto en la seguridad vial, el tráfico y el costo de la reparación. Por lo tanto, es crucial priorizar los baches más grandes y peligrosos para evitar accidentes y garantizar una circulación segura y eficiente.
El cálculo preciso y la correcta estimación de los materiales no solo optimizan los recursos, sino que también pueden servir como base para la toma de decisiones en políticas de mantenimiento y reparación vial, contribuyendo a la sostenibilidad económica y a la mejora de la infraestructura en zonas de alto tráfico.

A partir del codigo proporcionado podemos obtener visualizado los baches que queramos a partir de un archivo shapefile, esto se podria implementar por ejemplo en google maps avisandonos cada que nuestro vehiculo este cerca de algun bache peligroso y asi poder hacer realizar maniobras evasivas. Esto solo es un ejemplo en la cual la programacion geospacial podria ser utiizada para este proyecto.

Los resultados que arroja nuestro codigo son: 


![Resultado-Codigo](https://github.com/user-attachments/assets/c27b72cb-c611-4810-b8c5-ca9b1c5d3501)

Algo importante que se debe aclarar es que desde el inicio de la creacion del shapefile que contenga el poligono de los baches debe de estar en la proyeccion  EPSG:4326 de lo contrario el codigo proporcionado no servira completamente.

## Conclusiones
La investigación sobre la optimización del proceso de llenado de baches en la carretera Colima-Coquimatlán, específicamente a la altura del km 2.5, ha permitido identificar de manera precisa los beneficios de aplicar herramientas matemáticas como el cálculo integral para mejorar la eficiencia en las reparaciones viales. A través del análisis del volumen de los baches, calculado con la fórmula integral, se ha demostrado que este enfoque ofrece una forma precisa de determinar la cantidad exacta de material necesario para rellenar los baches, evitando el desperdicio de recursos y reduciendo los costos asociados a las reparaciones.
Los baches, debido a su impacto negativo en la seguridad vial, el flujo económico y el bienestar de la comunidad, representan un desafío crítico que afecta tanto a los ciudadanos como a las actividades económicas en la región. La optimización en su reparación no solo mejora la calidad de vida de los habitantes, sino que también favorece el desarrollo económico, especialmente en el sector del transporte, que es clave para la región. Además, el análisis ha demostrado que el tamaño y la profundidad de los baches tienen una correlación directa con la severidad de los problemas que generan, como los daños a vehículos y los riesgos de accidentes, lo que hace aún más importante el control eficiente de estos daños.

El uso del cálculo integral también ofrece una solución práctica a la complejidad de las formas irregulares de los baches. Mediante este método, se obtiene una estimación precisa del volumen del bache, lo que permite ajustar las reparaciones a las necesidades reales del pavimento, sin incurrir en sobrecostos por materiales sobrantes. Esto no solo optimiza el proceso de reparación, sino que también contribuye a la sostenibilidad económica y ambiental al reducir el impacto de la construcción en términos de recursos utilizados.

No obstante, la medición precisa de los baches en la carretera presenta ciertos riesgos debido a las condiciones de tránsito y visibilidad, lo que requiere que las personas encargadas de las mediciones tomen medidas de seguridad adecuadas, como el uso de señales reflectantes y ropa visible para evitar accidentes. Esta precaución es esencial para garantizar que las intervenciones se realicen de manera segura y eficiente.
En conclusión, la optimización del llenado de baches en la carretera Colima-Coquimatlán no solo mejora la infraestructura vial, sino que también tiene un impacto directo en la seguridad de los conductores, el flujo económico y la sostenibilidad ambiental de la región. Esta investigación proporciona un modelo que puede ser replicado en otras áreas con problemas similares, contribuyendo al desarrollo de infraestructuras más resilientes y eficientes a nivel regional y global.

El hecho de que exista un programa que te de la ubicación de los baches es algo bastante positvio, solo con que las coordenadas de los baches esten en el archivo shp tu puedes elegir tus rutas evitando los baches y asi proteger la economia de la sociedad en general. Tambien lo podrian usar los transportistas ya que asi pueden evitar caer en ellos, que se les dañe su camion y entegar sus mercancias tarde algo que genera una derrama economica negativa.  
