# PI2
<h2>PROYECTO INDIVIDUAL N02 </h2>
Contexto:<br>
La transmisión de información a través de medios electrónicos, como la telefonía, la televisión, la radio y, más recientemente, el internet permiten la transmisión de información entre distintos puntos.<br>
El internet, por su parte, es una red global de computadoras interconectadas que permite el intercambio de información en tiempo real.
Desde su creación, ha tenido un impacto significativo en la vida de las personas, transformando la manera en que nos comunicamos, trabajamos, aprendemos y nos entretenemos.<br>
Las telecomunicaciones han jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial.<br>
La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, y en casi cualquier lugar del mundo.<br>
En comparación con los medios mundiales, Argentina está a la vanguardia en el desarrollo de las telecomunicaciones, teniendo para el 2020 un total de 62,12 millones de conexiones.<br>
<h2>Limpieza de datos</h2>
Se descargo de la página de ENACOM, varios de sus archivos. Los cuales fueron trabajados de forma individual creando un archivo ipynb, para cada uno de ellos. Se realizo primero una limpieza detallada de cada base de datos y su posterior edición (Orden de columnas, tipo para cada columna, eliminación de registros nulos y  duplicados.<br>
Tambien se descargo la informacion detallada del ultimo censo en Argentina de la pagina del gobierno.<br>
Se fueron normalizando los datos, los nombres de las columnas, y se fue revisando detalladamente los valores atipicos. Se encontraron algunos valores outliers, los cuales fueron reemplazados, tomando el valor de la media como valor a aplicar.<br>
Se hicieron varios cambios a tipos de datos para su mejor uso en las consultas.<br>

Una vez finalizada esta etapa en cada base de datos, pase los datos utiles a archivos .csv, y tenerlos separados en su carpeta correspondiente para su posterior utilización.<br>

Librerías utilizadas para la limpieza de los datos.<br>
-	pandas para la lectura de cada archivo 
-	Warnings para ignorar las alertas de advertencia al ejecutar los códigos


Rol a desarrollar:<br>
En este contexto, un ente regulador de operadores de internet nos encarga la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. Considere que la principal actividad de la empresa es brindar acceso a internet , pero también es importante considerar el comportamiento asociado al resto de los servicios de comunicación, con el fin de orientar al ente contratista brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento. y poder plantear soluciones personalizadas a sus operadoras.<br>

Análisis exploratorio de datos [EDA]<br>
Principales Observaciones a tener en cuenta:<br>
Comparación entre Provincias: El analisis  ofrece una comparación rápida y sencilla del acceso a Internet entre las distintas provincias. Esto facilita la identificación de aquellas con mayor y menor acceso a la web, lo que puede ser valioso para la toma de decisiones estratégicas.<br>
Tendencias a lo Largo del Tiempo: Este analisis revela tendencias de acceso a Internet a lo largo del tiempo en cada provincia. Esto puede ayudar a determinar si el acceso está en aumento, disminución o se mantiene constante.<br>
Variaciones Estacionales: esta informacion posibilita la detección de variaciones estacionales en el acceso a Internet. Es fundamental para la planificación de iniciativas de mejora del servicio.<br>

Consideraciones finales:<br>
La utilizacion de graficos es una herramienta valiosa para la identificación de tendencias y comparaciones. No obstante, para una comprensión más profunda de los factores que influyen en estas tendencias, se requerirá un análisis más detallado. <br>
En resumen: Los gráficos proporcionan una representación clara y concisa del acceso a Internet en diferentes provincias a lo largo del tiempo. Es especialmente muy util para la toma de decisiones y la planificación estratégica, facilitando la visualización de tendencias y comparaciones de manera efectiva.<br>
Del analisis de la informacion generada, se indica un progreso continuo en la infraestructura de Internet y en la adopción de tecnologías más avanzadas en Argentina. Impactando positivamente en el acceso a la información, la comunicación y el desarrollo económico en el país. Es importante seguir monitoreando estas tendencias y aplicar acciones que garanticen que la conectividad a Internet siga siendo accesible y eficiente para todos los ciudadanos.<br>
Se denota una curva positiva para el avance en cuanto a la conectividad a internet dentro de la Argentina, pero existe una marcada diferencia entre zonas con mas densidad de poblacion y provincias con mas recursos economicos.<br>
