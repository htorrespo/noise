<!--

https://stackoverflow.com/questions/11256433/how-to-show-math-equations-in-general-githubs-markdownnot-githubs-blog

Complex Scalable Inline Rendering with LaTeX and Codecogs

If your needs are greater use an external LaTeX renderer like CodeCogs. Create an equation with CodeCogs editor (https://www.codecogs.com/latex/eqneditor.php). Choose svg for rendering and HTML for the embed code. Svg renders well on resize. HTML allows LaTeX to be easily read when you are looking at the source. Copy the embed code from the bottom of the page and paste it into your markdown.

<img src="https://latex.codecogs.com/svg.latex?\LARGE&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" title="\LARGE x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />
-->

# Resolucion 0627 de 2006

# Definiciones

_Horarios_: Para efectos de aplicación de esta resolución, para todo el
territorio nacional, se establecen los siguientes horarios.

- DIURNO: De las 7:01 a las 21:00 horas
- NOCTURNO: De las 21:01 a las 7:00 horas

_Unidades de Medida_: La pres ión sonora se expresa en Pascales, los
niveles de presión sonora se expresan en decibeles (dB). Las medidas deben indicar el
filtro de ponderación frecuencial utilizado (A, C, D u otro) y el filtro de ponderación
temporal F, S o I según sea rápida, lenta o de impulso (Fast, Slow o Impulse, en inglés).
Para todas las mediciones y cálculos, la presión sonora de referencia es 20 μPa.

_Parámetros de Medida_: Se establecen como parámetros principales para
la medida del ruido los siguientes:

- Nivel de presión sonora continúo equivalente ponderado A, LAeq,T y ponderado
lento (S).
- Ruido Residual, medido como nivel de presión sonora continuo equivalente
ponderado A, LAeq,T, Residual
- Nivel percentil L90

Sí por alguna razón no es posible medir el ruido residual, se toma como
valor el correspondiente al nivel percentil L90. En el informe técnico se deben especificar
las razones por las cuales no fue posible medir el ruido residual.

_Intervalo Unitario de Tiempo de Medida_: El intervalo unitario de tiempo
de medida T, para los niveles de presión sonora continuo equivalente con filtro de
ponderación frecuencial A, LAeq,T, del ruido residual y del nivel percentil L90,
se establece en una hora la cual puede ser medida
en forma continua o con intervalos de tiempo distribuidos uniformemente hasta obtener,
como mínimo, quince (15) minutos de captura de información.

Para la evaluación de la emisión de ruido de una o más fuentes, si la(s)
fuente(s) emisora(s) de ruido por su naturaleza o modo de operación, no permite(n)
efectuar las mediciones en los intervalos de tiempo mencionados, estas se deben
efectuar en el tiempo o tiempos correspondientes de operación de la(s) fuente(s),
relacionándose el hecho y el procedimiento seguido en el respectivo informe técnico.

_Ajustes_: Los niveles de presión sonora continuo equivalente ponderados A,
LAeq,T, LAeq,T, Residual y nivel percentil L90, se corrigen por impulsividad, tonalidad,
condiciones meteorológicas, horarios, tipos de fuentes y receptores, para obtener
niveles corregidos de presión sonora continuo equivalente ponderados A, LRAeq,T ,
LRAeq,T, Residual y nivel percentil L90, respectivamente.
Las correcciones, en decibeles, se efectúan de acuerdo con la siguiente ecuación para
los _**parámetros de medida**_,

<img src="https://latex.codecogs.com/svg.latex?\LARGE&space;L_{R&space;A(X),T}&space;=&space;L_{A(X),T}&space;&plus;&space;(K_I,&space;K_T,&space;K_R,&space;K_S)" title="\LARGE L_{R A(X),T} = L_{A(X),T} + (K_I, K_T, K_R, K_S)" />


Donde:

- KI es un ajuste por impulsos, dB(A)

- KT es un ajuste por tono y contenido de información, dB(A)

- KR es un ajuste por la hora del dí,dB(A)

- KS es un ajuste (positivo o negativo) para ciertas fuentes y situaciones, por
ejemplo bajas frecuencias, dB(A)

- (X) corresponde a cualquiera de los parámetros de medida de que trata la definicion.



El nivel de presión sonora continúo equivalent e ponderado A, LAeq,T, solo se corrige por
un solo factor K, el de mayor valor en dB(A).

La determinación de los valores de ajuste para los diferentes K se
efectúa de acuerdo con la metodología establecida en el Anexo 2.

Los niveles corregidos de presión sonora continuo equivalente
ponderados A, LRAeq,T, son los que se comparan con los estándares máximos
permisibles de emisión de ruido y ruido ambiental.

# Emision de ruido

_Aplicabilidad de la Emisión de Ruido_: Los resultados obtenidos en las
medidas de emisión de ruido, son utilizados para la verificación de los niveles de
emisión de ruido por parte de las fuentes. Las mediciones de la emisión de ruido se
efectúan en un _**intervalo unitario de tiempo de medida**_ y con el procedimiento 
descrito en el Anexo 3.

_Cálculo de la Emisión o Aporte de Ruido_: La emisión o aporte de ruido de
cualquier fuente se obtiene al restar logaritmicamente, el ruido residual corregido, del
valor del nivel de presión sonora corregido continuo equivalente ponderado A, LRAeq,T,
como se expresa a continuación:

<img src="https://latex.codecogs.com/svg.latex?\LARGE&space;Leq_{emision}&space;=&space;10\&space;log&space;(10&space;^{(LRAeq,1h)/10}&space;-\&space;10&space;^{(LRAeq,&space;1h,\&space;Residual)&space;/10})" title="\LARGE Leq_{emision} = 10\ log (10 ^{(LRAeq,1h)/10} -\ 10 ^{(LRAeq, 1h,\ Residual) /10})" />

Donde:

- Leqemisión: Nivel de emisión de presión sonora, o aporte de la(s) fuente(s)
sonora(s), ponderado A,

- LRAeq,1 h: Nivel corregido de presión sonora continúo equivalente ponderado A,
medido en una hora,

- LRAeq,1 h, Residual: Nivel corregido de presión sonora continuo equivalente ponderado A,
Residual, medido en una hora.

En caso de no poderse evaluar el ruido residual, se toma el nivel percentil
L90 corregido y se utiliza a cambio del valor del ruido residual corregido.

Estándares  máximos permisibles de niveles de
emisión de ruido expresados en decibeles ponderados A, dB(A),

Elaborar Tabla 1

Cuando la emisión de ruido en un sector o subsector, trascienda a
sectores o subsectores vecinos o inmersos en él, los estándares máximos permisibles
de emisión de ruido son aquellos que corresponden al sector o subsector más
restrictivo.

Las vías troncales, autopistas, vías arterias, vías principales, en
general las vías, son objeto de medición de ruido ambiental, más no de emisión de ruido
por fuentes móviles.

Las vías troncales, autopistas, vías arterias y vías principales, en
áreas urbanas o cercanas a poblados o asentamientos humanos, no se consideran
como subsectores inmersos en otras zonas o subsectores.

En los sectores y/o subsectores en que los estándares máximos
permisibles de emisión de ruido de la Tabla 1, son superados a causa de fuentes de
emisión naturales, sin que exista intervención del hombre, estos valores son
considerados como los estándares máximos p ermisibles, como es el caso de cascadas,
sonidos de animales en zonas o parques naturales.

_Ruido de Aeronaves_: Para efectos de la emisión de ruido de aeronaves
se tendrá en cuenta lo consagrado en la Resolución 2130 de 2004 de la Unidad
Administrativa Especial de Aeronáutica Civil o la que la adicione, modifique o sustituya.


_Ruido de Aeropuertos_: Los aeropuertos son considerados como sectores
industriales y el ruido debe ser evaluado según lo estipulado en la presente resolución
para este tipo de sectores.

# Ruido ambiental

_Aplicabilidad del Ruido Ambiental_: Los resultados obtenidos en las
mediciones de ruido ambiental, deben ser utilizados para realizar el diagnóstico del
ambiente por ruido. Los resultados se llevan a mapas de ruido los cuales permiten
visualizar la realidad en lo que concierne a ruido ambiental, identificar zonas críticas y
posibles contaminadores por emisión de ruido, entre otros. Las mediciones de ruido
ambiental se efectúan de acuerdo con el procedimiento estipulado en los Capítulos II y
III del Anexo 3.

_Intervalo de Tiempo de Referencia T_: Para la medida de los niveles de
presión sonora continuo equivalente ponderado A, -LAeq,T -, se establece como intervalo
de tiempo de referencia -T, catorce (14) horas para el horario diurno y diez (10) horas
para el horario nocturno, obteniéndose así los respectivos niveles, LAeq,d, diurno y LAeq,n, nocturno
independientes el uno del otro. Para las medid as de ruido en los intervalos de tiempo de
referencia se debe utilizar la metodología de medición del intervalo de tiempo de
medida unitario (por hora).

_Intervalo de Largo Plazo de Tiempo de Medida T_: Se establece un (1)
año calendario como el intervalo de largo plazo de tiempo de medida -T. No obstante, si
las aplicaciones del estudio ambiental que se realice son para períodos inferiores a un
(1) año; como en el caso de eventos especiales como carnavales, altas temporadas de
turismo, ferias y fiestas, entre otros, este intervalo de tiempo puede reducirse y deberá
especificarse claramente. Se debe escoger de modo que se cubran las variaciones de
la emisión de ruido.

Estándares máximos permisibles
de niveles de ruido ambiental expresados en decibeles ponderados A, dB(A).

Elaborar tabla 2

Se definen como v ías de alta circulación vehicular las
contempladas en la Ley 769 de 2002 como vías troncales, autopistas, vías arterias y
vías principales.

En los sectores y/o subsectores donde los estándares máximos
permisibles de ruido ambiental de la Tabla 2, son superados a causa de fuentes de
emisión naturales, sin que exista intervención del hombre, los estándares máximos
permisibles de ruido ambiental son los niveles de ruido naturales, como en el caso de
cascadas, sonidos de animales en zonas o parques naturales.

_Informe Técnico_: Los informes técnicos de las mediciones de emisión de
ruido y ruido ambiental, deben contener como mínimo la siguiente información:

- Fecha de la medición, hora de inicio y de finalización.
- Responsable del informe (Información mínima de quien lo hace).
- Ubicación de la medición
- Propósito de la medición.
- Norma utilizada (Si esta resolución u otra norma, en caso de ser otra especificar
razones)
- Tipo de instrumentación utilizado.
- Equipo de medición utilizado, incluyendo números de serie.
- Datos de calibración, ajuste del instrumento de medida y fecha de vencimiento
del certificado de calibración del pistófono.
- Procedimiento de medición utilizado.
- En caso de no ser posible la medición del ruido residual, las razones por las
cuales no fue posible apagar la fuente.
- Condiciones predominantes.
- Condiciones atmosféricas (dirección y velocidad del viento, lluvia, temperatura,
presión atmosférica, humedad).
- Procedimiento para la medición de la velocidad del viento.
- Naturaleza / estado del terreno entre la fuente y el receptor; descripción de las
condiciones que influyen en los resultados: acabados de la superficie, geometría,
barreras y métodos de control existentes, entre otros.
- Resultados numéricos y comparación con la normatividad aplicada.
- Descripción de los tiempos de medición, intervalos de tiempos de medición y de
referencia, detalles del muestreo utilizado.
- Variabilidad de la(s) fuente(s).
- Descripción de las fuentes de sonido existentes, datos cualitativos.
- Reporte de memoria de cálculo (incertidumbre, ajustes, aporte de ruido, entre
otros).
- Conclusiones y recomendaciones.
- Croquis detallado que muestre la posición de las fuentes de sonido, objetos
relevantes y puntos de observación y medición.
- Copia de los certificados de calibración electrónica de los equipos.

Estos informes deben estar disponibles para su revisión y evaluación por parte de las
autoridades competentes. En el Anexo 4 se presenta un modelo de formato para la
elaboración del informe técnico de medición de ruido.

# ANEXO 1

**Definiciones**


_Acústica_: Rama de la ciencia que trata de las perturbaciones elásticas sonoras.
Originalmente aplicada sólo a los sonidos audibles.

_Ajuste (de un instrumento de medición)_: operación destinada a poner un instrumento
de medición en estado de funcionamiento adecuado para su uso. El ajuste puede ser
automático, semiautomático o manual.

_Alarma_: Mecanismo que, por diversos procedimientos, tiene por función avisar de algo.

_Ancho de banda_: Extensión del espectro de las frecuencias comprendidas en el interior
de una banda. Se mide por la diferencia entre las frecuencias extremas de aquella.

_Autopista_: Vía de calzadas separadas, cada una con dos (2) o más carriles, control
total de acceso y salida, con intersecciones en desnivel o mediante entradas y salidas
directas a otras carreteras y con control de velocidades mínimas y máximas por carril.

_Banda de octava_: Es un grupo de frecuencias en torno a una banda central que
cumplen la relación f2 = 2 f1 y además, fc = fc (f1x f2)^1/2  son las frecuencias centrales, que
toman valores normalizados según la Norma ISO-266-75. La percepción del oído
humano contiene aproximadamente 10 bandas de octava.

Calibración: Conjunto de operaciones que establecen, bajo condiciones especificadas, la
relación entre los valores de magnitudes indicados por un instrumento o sistema de
medición, o valores representados por una medida materializada o un material de
referencia y los correspondientes valores reportados por patrones. El resultado de la
calibración permite tanto la asignación de valores a las indicaciones de la magnitud a
medir como la determinación de las correcciones con respecto a las indicaciones. Una
calibración también puede determinar otras propiedades metrológicas, tales como el
efecto de las magnitudes influyentes. El resultado de una calibración puede ser registrado
en un documento, frecuentemente denominado certificado de calibración o informe de
calibración.

_Calibrador_: Ver definición de Pistófono.


_Campo sonoro_: Es la región del espacio en las que existen perturbaciones elásticas.

_dB(A)_: Unidad de medida de nivel sonoro con ponderación frecuencial (A).

_Decibel (dB)_: Décima parte del Bel, razón de energía, potencia o intensidad que
cumple con la siguiente expresión: Log R = 1dB/10
Donde R = razón de energía, potencia o intensidad

_Emisión de Ruido_: Es la presión sonora que generada en cualesquiera condiciones,
trasciende al medio ambiente o al espacio público.

_Espacio público_: Conjunto de inmuebles públicos y los elementos arquitectónicos y
naturales de los inmuebles privados, destinados por su naturaleza, por su uso o
afectación, a la satisfacción de necesidades urbanas colectivas que trascienden, por
tanto, los estándares de los intereses individuales de los habitantes.

Complementar ...

# ANEXO 2

**Determminacion de los valores de ajuste K**

1. La corrección de nivel KS se aplica de la siguiente manera:
2. 
- Si el ruido proviene de las instalaciones de ventilación y climatización, bajas
frecuencias:
- 5 dB(A) en período diurno;
- 8 dB(A) en período nocturno.
- 
2. La corrección de nivel KR por horarios se aplica de la siguiente manera:
Si se desea calcular el nivel equivalente corregido ponderado por frecuencia A para el
día y la noche LRAeq, dn, se efectúa la medición nocturna de ruido de la fuente específica,
si esta funciona durante la noche, para tener en cuenta el grado de molestia que pueda
causar a las personas se hace una corrección por adición de 10 dB(A) para el período
nocturno en el cual funcione la fuente específica.

3. La corrección de nivel KT toma en consideración los componentes tonales del ruido
en el lugar de la medición y durante el tiempo que estén presentes estos tonos.

- Por percepción nula de componentes tonales: 0 dB(A).
- Por percepción neta de componentes tonales: 3 dB(A).
- Por percepción fuerte de componentes tonales: 6 dB(A).

4. La corrección de nivel KI toma en consideración los componentes impulsivos en el
lugar de la medición y durante el tiempo que estén presentes los respectivos impulsos.

- Por percepción nula de componentes impulsivos: 0 dB(A).
- Por percepción neta de componentes impulsivos: 3 dB(A).
- Por percepción fuerte de componentes impulsivos: 6 dB(A).
5. La manera detallada de evaluar la presencia de componentes tonales se presenta a
continuación:
- Se hace un análisis con resolución de 1/3 de octava.
- Se calcula la diferencia:

L = Lt - Ls

Donde:

Lt es el nivel de presión sonora de la banda f que contiene el tono puro;

Ls es la media de los niveles de las dos bandas situadas inmediatamente por encima y
por debajo de f.

Se determina la presencia o ausencia de componentes tonales, entre 20 a 125 Hz:

- Si L < 8 dB(A), no hay componentes tonales.
- Si 8 dB(A)  L  12 dB(A), hay componente tonal neto.
- Si L > 12 dB(A), hay componente tonal fuerte.

Se determina la presencia o ausencia de componentes tonales, entre 160 a 400 Hz:




