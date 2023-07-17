<div align="center"><a href="https://www.escuelaing.edu.co/es/investigacion-e-innovacion/centro-de-estudios-en-sistemas-termicos-y-mecanicos/" target="_blank"><img src="https://github.com/OVenegas2984/Motores-Reciprocos/blob/main/.icon/IconCESTYMBanner.svg" alt="Motores-Reciprocos" width="100%" border="0" /></a></div>

<div align="center">
<br><b>Motores de Combustión Interna Alternativos</b><br><br><b>Universidad Escuela Colombiana de Ingeniería Julio Garavito</b><br>Ph.D. Ing. Oscar Hernando Venegas Pereira<br>Profesor del Centro de Estudios en Sistemas Térmicos y Mecánicos<br>oscar.venegas@escuelaing.edu.co<br>
</div><br>


## Introducción a los Motores Recíprocos
Keywords: `Mecanismo biela-manivela` `Hydrology` `Evapotranspiration` `Rain` `Area`



<br>Explicación general del procedimiento para la realización de balances hidrológicos e identificación de información base requerida. En esta clase también se listan algunas de las aplicaciones generales de los caudales medios de largo plazo en la realización de estudios de ingeniería y estudios ambientales

Los balances hidrológicos de largo plazo permiten cuantificar la oferta hídrica superficial o el caudal medio en cualquier localización particular o sobre un área específica de interés. Para la ejecución completa de un balance hidrológico de largo plazo a nivel anual, es necesario definir primero el límite espacial de la zona de estudio para luego obtener los mapas de terreno, redes de drenaje y series hidroclimatológicas necesarias para la producción de mapas continuos.

<div align="center"><br><a href="http://www.youtube.com/watch?feature=player_embedded&v=g5Dvm9IYhOg" target="_blank"><img src="https://github.com/rcfdtools/R.TeachingResearchGuide/blob/main/CaseUse/.icons/IconCEHYouTubeInicioActividad.png" alt="R.LTWB" width="75%" border="0" /></a><sub><br>Playlist: https://www.youtube.com/playlist?list=PLneiG4vC_8YupZFL2DtUEdcgtXyWT7Apt</sub><br><br></div>


## Máquina de combustión interna

Los balances hidrológicos de largo plazo son frecuentemente utilizados en estudios hidrológicos y ambientales debido a que a través de ellos es posible: 

* Estimar el caudal medio superficial disponible en cuencas hidrográficas o en localizaciones particulares de la red de drenaje.
* Obtener ecuaciones características que relacionan áreas de aportación vs. caudales medios.
* Estimar isorendimientos medios.
* Estimar caudales para concesión por captación y vertimiento.
* Estimar caudales ecológicos.
* Obtener valores de referencia para el diseño de estructuras ecológicas.


## Máquina de combustión externa

Para la estimación de caudales medios, se realiza un balance hidrológico de largo plazo en cada una de las celdas que cubre la zona de estudio. Se denomina de largo plazo, debido a que se asume que luego de ser saturado el suelo, la escorrentía se produce por los excedentes de precipitación que no son evapotranspirados.

> Es importante tener en cuenta que en algunas zonas particulares, se pueden obtener déficits debido a que el valor estimado o medido de la evapotranspiración puede ser mayor al valor de precipitación disponible.

La siguiente expresión permite determinar el caudal medio en cada celda de terreno, en el que, al valor estimado de precipitación, se le resta la abstracción correspondiente a la evapotranspiración real. El valor correspondiente al área sobre la cual se estima el caudal, corresponde al total de celdas convergentes (en cada localización del terreno) multiplicadas por el tamaño de cada pixel, el cual es definido por la resolución espacial de las grillas utilizadas.

<div align="center">

Qm = (( P – E ) * A) / t

</div>

Donde,

* Qm: caudal medio, m³/s
* P: precipitación, mm/año
* E: evapotranspiración real, mm/año
* A: área de cada celda, m²
* t: tiempo en segundos en un año, (365 dias x 24 horas x 60 minutos x 60 segundos = 31.536.000.000)

El cálculo computacional del LTWB, puede ser desarrollado con cualquier software SIG que disponga de herramientas para reacondicionamiento de modelos de terreno, creación de mosaicos, algebra de mapas y herramientas de análisis espacial. Algunas de las actividades de este curso han sido desarrolladas utilizando QGIS, ArcGIS for Desktop, ArcGIS Pro, HEC-GeoHMS y HEC-HMS.


## Referencias

* [Unesco. (1981). Métodos de cálculo del balance hídrico.](https://unesdoc.unesco.org/ark:/48223/pf0000137771)
* [UPM. Evapotranspiración real](http://ocw.upm.es/pluginfile.php/675/mod_label/intro/Evapotranspiracion-real.pdf)
* [Sociedad Geográfica de Lima. (2011). Balance hídrico superficial.](https://www.gwp.org/globalassets/global/gwp-sam_files/publicaciones/varios/balance_hidrico.pdf)


| [Actividad anterior](../../Readme.md) | [:house: Inicio](../../Readme.md) | [:beginner: Ayuda / Colabora](https://github.com/rcfdtools/R.LTWB/discussions/38) | [Actividad siguiente](../Requirement) |
|---------------------------------------|-----------------------------------|------------------------------------------------------------------------|---------------------------------------|



##

<div align="center"><a href="http://www.escuelaing.edu.co" target="_blank"><img src="https://github.com/OVenegas2984/Motores-Reciprocos/blob/main/.icon/LogoEscuela.svg" alt="Support by" width="100%" border="0" /></a><sub><br>Este curso guía ha sido desarrollado con el apoyo de la Universidad Escuela Colombiana de Ingeniería Julio Garavito. Encuentra más contenidos en https://github.com/uescuelaing</sub><br><br></div>
