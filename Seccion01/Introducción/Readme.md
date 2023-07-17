<div align="center"><a href="https://www.escuelaing.edu.co/es/investigacion-e-innovacion/centro-de-estudios-en-sistemas-termicos-y-mecanicos/" target="_blank"><img src="https://github.com/OVenegas2984/Motores-Reciprocos/blob/main/.icon/IconCESTYMBanner.svg" alt="Motores-Reciprocos" width="100%" border="0" /></a></div>

<div align="center">
<br><b>Motores de Combustión Interna Alternativos</b><br><br><b>Universidad Escuela Colombiana de Ingeniería Julio Garavito</b><br>Ph.D. Ing. Oscar Hernando Venegas Pereira<br>Profesor del Centro de Estudios en Sistemas Térmicos y Mecánicos<br>oscar.venegas@escuelaing.edu.co<br>
</div><br>


## Introducción a los Motores Recíprocos
Keywords: `Internal Combustion Engine` `Reciprocating engine` `Mechanical Energy` `Chemical Energy` `Combustion`

<p style="text-align: justify;">Las máquinas térmicas han desempeñado un papel fundamental en la historia de la humanidad, ya que han sido un factor clave para el desarrollo de la industria y el avance tecnológico. A lo largo del tiempo, se han seguido desarrollando máquinas térmicas cada vez más eficientes y con diversas con aplicaciones que van desde el transporte terrestre, la propulsión de aviones y la generación de energía eléctrica.</p>

A pesar del crecimiento de la movilidad eléctrica y otras tecnologías, las máquinas de combustión siguen siendo ampliamente utilizadas en la actualidad en diferentes áreas de la industria en general, aunque se espera que su uso graduclamente siga incorporando fuentes de energía más limpias y sostenibles en pro del bienestar de la sociedad. Un tipo particular de máquina térmica, son los motores recíprocos o alternativos (también conocidos como motores de pistón), los cuales convierten la energía química del combustible en energía mecánica a través de un proceso cíclico al interior del cilindro. 

Estos motores recíprocos han sido fundamentales en la industria y el transporte, impulsando automóviles, aviones, embarcaciones y una amplia variedad de maquinarias y a los largo del tiempo han experimentado una evolución continua, mejorando en eficiencia, rendimiento y reducción de emisiones, encontrándose así hoy día motores más amigables con el medio ambiente llevando a cabo una transición hacia fuentes de energía más sostenibles y menos dependientes de los combustibles fósiles en el futuro.

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

<div align="center"><a href="http://www.escuelaing.edu.co" target="_blank"><img src="https://github.com/OVenegas2984/Motores-Reciprocos/blob/main/.icon/LogoEscuela.svg" alt="Support by" width="25%" border="0" /></a><sub><br>Este curso guía ha sido desarrollado con el apoyo de la Universidad Escuela Colombiana de Ingeniería Julio Garavito. Encuentra más contenidos en https://github.com/uescuelaing</sub><br><br></div>
