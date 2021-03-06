<!--

https://stackoverflow.com/questions/11256433/how-to-show-math-equations-in-general-githubs-markdownnot-githubs-blog

Complex Scalable Inline Rendering with LaTeX and Codecogs

If your needs are greater use an external LaTeX renderer like CodeCogs. Create an equation with CodeCogs editor (https://www.codecogs.com/latex/eqneditor.php). Choose svg for rendering and HTML for the embed code. Svg renders well on resize. HTML allows LaTeX to be easily read when you are looking at the source. Copy the embed code from the bottom of the page and paste it into your markdown.

<img src="https://latex.codecogs.com/svg.latex?\LARGE&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" title="\LARGE x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />
-->

# Apuntes de la Resolucion 627 de 7 de abril de 2006

*Por la cual se establece la norma nacional de emisión de ruido y ruido ambiental. Ministerio de Ambiente Vivienda y Desarrollo Territorial. Colombia*

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

<img src="https://latex.codecogs.com/svg.latex?\inline&space;\huge&space;L_{eq_{emision}}&space;=&space;10\&space;log&space;(10&space;^{(L_{RAeq,1h})/10}&space;-\&space;10&space;^{(L_{RAeq,1h,Residual})/10})" title="\huge L_{eq_{emision}} = 10\ log (10 ^{(L_{RAeq,1h})/10} -\ 10 ^{(L_{RAeq,1h,Residual})/10})" />

Donde:

- Leqemisión: Nivel de emisión de presión sonora, o aporte de la(s) fuente(s)
sonora(s), ponderado A,

- LRAeq,1 h: Nivel corregido de presión sonora continúo equivalente ponderado A,
medido en una hora,

- LRAeq,1 h, Residual: Nivel corregido de presión sonora continuo equivalente ponderado A,
Residual, medido en una hora.

En caso de no poderse evaluar el ruido residual, se toma el nivel percentil
L90 corregido y se utiliza a cambio del valor del ruido residual corregido.

*Tabla 1. Estándares  máximos permisibles de niveles de
emisión de ruido expresados en decibeles ponderados A, dB(A)*

| Sector | Subsector | Dia dB(A) | Noche dB(A) |
|--------|-----------|:---------:|:-----------:|
| Sector A. Tranquilidad y Silencio | Hospitales bibliotecas, guarderías, sanatorios, hogares geriátricos. | 55 | 50 |
| Sector B. Tranquilidad y Ruido Moderado | Zonas residenciales o exclusivamente destinadas para desarrollo habitacional, hotelería y hospedajes. | 65 | 55 |
| Sector B. Tranquilidad y Ruido Moderado | Universidades, colegios, escuelas, centros de estudio e investigación.| 65 | 55 |
| Sector B. Tranquilidad y Ruido Moderado | Parques en zonas urbanas diferentes a los parques mecánicos al aire libre.| 65 | 55 |
| Sector C. Ruído Intermedio Restringido | Zonas con usos permitidos industriales, como industrias en general, zonas portuarias, parques industriales, zonas francas.| 75 | 75 |
| Sector C. Ruído Intermedio Restringido | Zonas con usos permitidos comerciales, como centros comerciales, almacenes, locales o instalaciones de tipo comercial, talleres de mecánica automotriz e industrial, centros deportivos y recreativos, gimnasios, restaurantes, bares, tabernas, discotecas, bingos, casinos. | 70 | 60 |
| Sector C. Ruído Intermedio Restringido | Zonas con usos permitidos de oficinas. | 65 | 55 |
| Sector C. Ruído Intermedio Restringido | Zonas con usos institucionales. | 65 | 55 |
| Sector C. Ruído Intermedio Restringido | Zonas con otros usos relacionados, como parques mecánicos al aire libre, áreas destinadas a espectáculos públicos al aire libre. | 80 | 75 |
| Sector D. Zona Suburbana o Rural de Tranquilidad y Ruído Moderado | Residencial suburbana. | 55 | 50 |
| Sector D. Zona Suburbana o Rural de Tranquilidad y Ruído Moderado | Rural habitada destinada a explotación agropecuaria. | 55 | 50 |
| Sector D. Zona Suburbana o Rural de Tranquilidad y Ruído Moderado | Zonas de Recreación y descanso, como parques naturales y reservas naturales. | 55 | 50 |



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

*Tabla 2. Estándares máximos permisibles
de niveles de ruido ambiental expresados en decibeles ponderados A, dB(A)*

| Sector | Subsector | Dia dB(A) | Noche dB(A) |
|--------|-----------|:---------:|:-----------:|
| Sector A. Tranquilidad y Silencio | Hospitales bibliotecas, guarderías, sanatorios, hogares geriátricos. | 55 | 45 |
| Sector B. Tranquilidad y Ruido Moderado | Zonas residenciales o exclusivamente destinadas para desarrollo habitacional, hotelería y hospedajes. | 65 | 50 |
| Sector B. Tranquilidad y Ruido Moderado | Universidades, colegios, escuelas, centros de estudio e investigación.| 65 | 50 |
| Sector B. Tranquilidad y Ruido Moderado | Parques en zonas urbanas diferentes a los parques mecánicos al aire libre.| 65 | 50 |
| Sector C. Ruído Intermedio Restringido | Zonas con usos permitidos industriales, como industrias en general, zonas portuarias, parques industriales, zonas francas.| 75 | 70 |
| Sector C. Ruído Intermedio Restringido | Zonas con usos permitidos comerciales, como centros comerciales, almacenes, locales o instalaciones de tipo comercial, talleres de mecánica automotriz e industrial, centros deportivos y recreativos, gimnasios, restaurantes, bares, tabernas, discotecas, bingos, casinos. | 70 | 55 |
| Sector C. Ruído Intermedio Restringido | Zonas con usos permitidos de oficinas. | 65 | 50 |
| Sector C. Ruído Intermedio Restringido | Zonas con usos institucionales. | 65 | 50 |
| Sector C. Ruído Intermedio Restringido | Zonas con otros usos relacionados, como parques mecánicos al aire libre, áreas destinadas a espectáculos públicos al aire libre. | 80 | 70 |
| Sector D. Zona Suburbana o Rural de Tranquilidad y Ruído Moderado | Residencial suburbana. | 55 | 45 |
| Sector D. Zona Suburbana o Rural de Tranquilidad y Ruído Moderado | Rural habitada destinada a explotación agropecuaria. | 55 | 45 |
| Sector D. Zona Suburbana o Rural de Tranquilidad y Ruído Moderado | Zonas de Recreación y descanso, como parques naturales y reservas naturales. | 55 | 45 |




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

## Definiciones


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
cumplen la relación f2 = 2 x f1 y además, fc = fc (f1x f2)^1/2  son las frecuencias centrales, que
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

_Espacio privado_: Se ha de entender no solo como aquel sobre el cual ejerce dominio,
mediante su propiedad, un grupo o persona determinada, sino como una espacialidad
que tiene características diferentes y que está compuesta en primer lugar del espacio
individual, que proporciona la intimidad y cuyo acceso es prohibido (negativo), limitado,
como la vivienda como su más estrecha acepción: el techo. Bajo esta nominación se
incluyen además todas aquellas espacialidades que tienen un acceso limitado por la
propiedad del mismo como son los lugares de trabajo, oficinas, fábricas y en general
todos aquellos espacios sobre los cuales existe un estricto control por parte del interés
particular.

_Especificación_: Exigencia o requisito que debe cumplir un producto, un proceso o un
servicio. Una especificación puede ser una norma, pero generalmente es parte de una
norma.

_Filtros de Tercios de Octava_: dispositivo que permite efectuar análisis de una la señal
acústica, en bandas de tercios de octava.

_Frecuencia (ƒ) (Hz)_: En una función periódica en el tiempo, es el número de ciclos
realizados en la unidad de tiempo (ƒ = c/s). La frecuencia es la inversa del período. La
unidad es el Hertzio (Hz) que es igual a l/S.

_Fuente_: Elemento que origina la energía mecánica vibratoria, definida como ruido o
sonido. Puede considerarse estadísticamente como una familia de generadores de
ruido que pueden tener características físicas diferentes, distribuidas en el tiempo y en
el espacio.

_Hertzio (Hz)_: Es la unidad de frecuencia, equivalente al ciclo por segundo ( c/s). Un
fenómeno periódico de 1 segundo de período tiene frecuencia 1 Hz.

_Incertidumbre de medición_: Parámetro, asociado al resultado de una medición, que
caracteriza la dispersión de los valores que pudieran ser razonablemente atribuidos a la
magnitud a medir. El parámetro puede ser, por ejemplo, la desviación típica (o un múltiplo
de ésta), o la amplitud del intervalo de confianza. La incertidumbre de medición
comprende, en general, muchos componentes. Algunos de ellos pueden ser evaluados a
partir de la distribución estadística de los resultados de series de mediciones y pueden ser
caracterizados mediante desviaciones típicas experimentales. Los otros componentes,
que pueden también ser caracterizados por desviaciones típicas, son evaluados a partir de
distribuciones de probabilidad asumida, basadas en la experiencia u otra información. Se
entiende que el resultado de la medición es el mejor estimado del valor de la magnitud a
medir y de todos los componentes de la incertidumbre que contribuyen a la dispersión,
incluyendo aquellos que surgen de los efectos sistemáticos tales como los componentes
asociados con las correcciones y los patrones de referencia.

_Índices de ruido_: Diversos parámetros de medida cuya aplicación está en función de la
fuente productora del ruido y el medio donde incide. Ejemplos: Leq, L10, L90, TNI.

_Leq_. Nivel sonoro continuo equivalente, es el nivel en dBA de un ruido constante
hipotético correspondiente a la misma cantidad de energía acústica que el ruido real
considerado, en un punto determinado durante un período de tiempo T y su expresión
matemática es:

<img src="https://latex.codecogs.com/svg.latex?\inline&space;\huge&space;L_{eq}&space;=&space;10\&space;log&space;\left&space;[&space;\frac{1}{T}&space;\sum&space;t_1&space;10^{L_i/10}&space;\right&space;]" title="\huge L_{eq} = 10\ log \left [ \frac{1}{T} \sum t_i 10^{L_i/10} \right ]" />

Donde:

ti es el tiempo de observación durante el cual el nivel sonoro es Li ± 2 dBA.

L10: Es el nivel sonoro en dBA que se sobrepasa durante el 10% del tiempo de
observación. L10= L50+1,28s (dBA).

L90.: Es el nivel sonoro en dBA que se sobrepasa durante el 90% del tiempo de
observación. L90=L50-1,28s (dBA).

LRAeq,T.: Es el nivel corregido de presión sonora continuo equivalente ponderado A,
evaluado en un periodo de tiempo (T).

LAeq,T, d.: Es el nivel de presión sonora continuo equivalente ponderado A, evaluado en
periodo diurno.

LAeq,T, n: Es el nivel de presión sonora continuo equivalente ponderado A, evaluado en
periodo nocturno.

_Mapas de ruido_: Se entiende por mapa de ruido, la representación de los datos sobre
una situación acústica existente o pronosticada en función de un indicador de ruido, en
la que se indica la superación de un valor límite, el número de personas afectadas en
una zona dada y el número de viviendas, centros educativos y hospitales expuestos a
determinados valores de ese indicador en dicha zona.

_Medio ambiente_: Es el conjunto de componentes físicos, químicos, biológicos y
sociales capaces de causar efectos directos o indirectos, en un plazo corto o largo,
sobre los seres vivos y las actividades humanas.

_Motocicleta_: Vehículo automotor de dos ruedas en línea, con capacidad para el
conductor y un acompañante.

_Nivel (L)_: En acústica, la incorporación del término Nivel a una magnitud, quiere decir
que se está considerando el logaritmo decimal del cociente del valor de la magnitud con
respecto a otro valor de la misma, tomado como referencia.

_Nivel de presión sonora (Lp) (dB)_: Es la cantidad expresada en decibeles y calculada
según la siguiente ecuación:

<img src="https://latex.codecogs.com/svg.latex?\inline&space;\huge&space;L_{p}(dB)&space;=&space;20\&space;log\&space;\frac{P}{P_0}" title="\huge L_{p}(dB) = 20\ log\ \frac{P}{P_0}" />

Donde:

P = valor cuadrático medio de la presión sonora.

P0 = presión sonora de referencia, en el aire. (2x10^-5 Pascales)

_Nivel sonoro_: Es el nivel de presión sonora obtenido mediante las redes de
ponderación A, B o C. La presión de referencia es 2 x10^-5 Pa.

_Norma_: Solución que se adopta para resolver un problema específico, así la norma es
una referencia respecto a la cual se juzgará un tema específico o una función y es el
resultado de una decisión colectiva y razonada. La NORMA es un documento resultado
del trabajo de muchas personas por mucho tiempo y la NORMALIZACIÓN es la
actividad conducente a la elaboración, aplicación, y mejoramiento de las normas.

_Norma de emisión de ruido_: Es el valor máx imo permisible de presión sonora, definido
para una fuente, por la autoridad ambiental competente, con el objeto de cumplir la
norma de ruido ambiental.

_Norma de ruido ambiental_: Es el valor establecido por la autoridad ambiental
competente, para mantener un nivel permisible de presión sonora, según las
condiciones y características de uso del sector, de manera tal que proteja la salud y el
bienestar de la población expuesta, dentro de un margen de seguridad.

_Octava_: Intervalo entre dos frecuencias cuya relación es 2. Es corriente medir en
octavas el intervalo que separa dos frecuencias cualesquiera; para ello, basta hallar el
logaritmo en base 2 de la relación de frecuencias.

_Paramento_: Cada una de las dos caras de una pared.

_Pascal (Pa)_: Unidad de presión en el sistema MKS equivalente a: 1 Newton / m2 = 10
barias.

_Plan de Ordenamiento Territorial (POT)_: Instrumento básico para desarrollar el
proceso de ordenamiento del territorio municipal y se define como el conjunto de
objetivos, directrices, políticas, estrategias, metas, programas, actuaciones y normas
adoptadas para orientar y administrar el desarrollo físico del territorio y la utilización del
suelo.

_Pistófono_: Es una pequeña cavidad provista de un pistón con movimiento de vaivén y
desplazamiento medible, que permite establecer una presión conocida en el interior de
la cavidad. Generalmente utilizado para efectuar calibraciones de sonómetros.

_Pito_: Instrumento de metal, que se hace sonar mecánicamente en los automóviles y
otros artefactos.

_Presión sonora_: Es la diferencia entre la presión total instantánea en un punto cuando
existe una onda sonora y la presión estática en dicho punto.

_Pretil_: Murete de piedra u otra materia que se pone en los puentes y en otros lugares
para preservar de caídas.

_Reflexión_: Es el fenómeno por el cual una onda después de incidir sobre una
superficie, se propaga en el mismo medio con sentido diferente al anterior. El rayo
reflejado forma con la normal a la superficie reflectora el mismo ángulo que forma el
rayo incidente con dicha normal.

_Ruido acústico_: Es todo sonido no deseado por el receptor. En este concepto están
incluidas las características físicas del ruido y las psicofisiológicas del receptor, un
subproducto indeseable de las actividades normales diarias de la sociedad.

_Ruido de Baja Frecuencia_: Es aquel que posee una energía acústica significante en el
intervalo de frecuencias de 8 a 100 Hz. Este tipo de ruido es típico en grandes motores
diesel de trenes, barcos y plantas de energía y, puesto que este ruido es difícil de
amortiguar, se extiende fácilmente en todas direcciones y puede ser oído a muchos
kilómetros.

_Ruido de fondo_: Ruido total de todas las fuentes de interferencia en un sistema
utilizado para producción, medida o registro de una señal, independiente de la
presencia de la señal, incluye ruido eléctrico de los equipos de medida. El ruido de
fondo se utiliza algunas veces para expresar el nivel medido cuando la fuente específica
no es audible y, a veces, es el valor de un determinado parámetro de ruido, tal como el
L90 (nivel excedido durante el 90% del tiempo de medición).

_Ruido específico_: Es el ruido procedente de cualquier fuente sometida a investigación.
Dicho ruido es un componente del ruido ambiental y puede ser identificado y asociado
con el foco generador de molestias.

_Ruido Impulsivo_: Es aquel en el que se presentan variaciones rápidas de un nivel de
presión sonora en intervalos de tiempo mínimos, es breve y abrupto, por ejemplo,
troqueladoras, pistolas, entre otras.

_Ruido residual_: Ruido total cuando los ruidos específicos en consideración son
suspendidos. El ruido residual es el ruido ambiental sin ruido específico. No debe
confundirse con el ruido de fondo.

_Ruido Tonal_: Es aquél que manifiesta la presencia de componentes tonales, es decir,
que mediante un análisis espectral de la señal en 1/3 (un tercio) de octava, si al menos
uno de los tonos es mayor en 5 dBA que los adyacentes, o es claramente audible, la
fuente emisora tiene características tonales. Frecuentemente las máquinas con partes
rotativas tales como motores, cajas de cambios, ventiladores y bombas, crean tonos.
Los desequilibrios o impactos repetidos causan vibraciones que, transmitidas a través
de las superficies al aire, pueden ser oídos como tonos.

_Sirena_: Pito que se oye a mucha distancia y que se emplea en los buques, automóviles,
fábricas, etc., para avisar.

_Sonido_: Sensación percibida por el órgano auditivo, debida generalmente a la
incidencia de ondas de comprensión (longitudinales) propagadas en el aire. Por
extensión se aplica el calificativo del sonido, a toda perturbación que se propaga en un
medio elástico, produzca sensación audible o no.

_Sonómetro_: Es un instrumento de medición de presión sonora, compuesto de
micrófono, amplificador, filtros de ponderación e indicador de medida, destinado a la
medida de niveles sonoros, siguiendo unas determinadas especificaciones.

_Tercios de Octava_: Tercera parte de una banda de octava y grupo de frecuencias en
torno a una banda central que cumplen la relación f2 = f1 x 2^1/3 y fc = fc (f1 x f2)^1/2 son las
frecuencias centrales, que toman valores normalizados según la Norma ISO-266-75.
Tono puro: 1) Es una onda sonora cuya presión sonora instantánea es una función
sinusoidal simple del tiempo y 2) Es una sensación sonora caracterizada por tener una
única altura tonal.

_Tonos en el Ruido (tonalidad)_: Los tonos molestos pueden verse generados de dos
maneras: Frecuentemente las máquinas con partes rotativas tales como motores, cajas
de cambios, ventiladores y bombas, crean tonos. Los desequilibrios o impactos
repetidos causan vibraciones que, transmitidas a través de las superficies al aire,
pueden ser oídos como tonos. También pueden generar tonos los flujos pulsantes de
líquidos o gases que se producen por causa de procesos de combustión o restricciones
de flujo.

_Umbral de audición_: Es la mínima presión sonora eficaz que debe tener una señal
para dar origen a una sensación auditiva, en ausencia de todo ruido. Se expresa
generalmente en dB.


_Unidad de medida_: Magnitud particular, definida y adoptada por convenio, con la cual
son comparadas otras magnitudes del mismo tipo para expresar la cantidad relativa a esa
magnitud. Las unidades de medida tienen asignados convencionalmente nombres y
símbolos. Las unidades de las magnitudes de la misma dimensión pueden tener los
mismos nombres y símbolos aún cuando las magnitudes no sean del mismo tipo.

_Vehículo_: Todo aparato montado sobre ruedas que permite el transporte de personas,
animales o cosas de un punto a otro por vía terrestre pública o privada abierta al
público.

_Vía_: Zona de uso público o privado, abierta al público, destinada al tránsito de
vehículos, personas y animales.

_Vía arteria_: Vía de un sistema vial urbano con prelación de circulación de tránsito sobre
las demás vías, con excepción de la vía férrea y la autopista.

_Vía principal_: Vía de un sistema con prelación de tránsito sobre las vías ordinarias.
Vía ordinaria: La que tiene tránsito subordinado a las vías principales.

_Vía troncal_: Vía de dos (2) calzadas con ocho o más carriles y con destinación
exclusiva de las calzadas interiores para el tránsito de servicio público masivo.
Vías de alta circulación vehicular: Las contempladas en la Ley 769 de 2002 como
vías troncales, autopistas, vías arterias y vías principales.


# ANEXO 2

## Determinacion de los valores de ajuste K

1. La corrección de nivel KS se aplica de la siguiente manera:

- Si el ruido proviene de las instalaciones de ventilación y climatización, bajas
frecuencias:
- 5 dB(A) en período diurno;
- 8 dB(A) en período nocturno.

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

<img src="https://latex.codecogs.com/svg.latex?\inline&space;\huge&space;L&space;=&space;L_t&space;-&space;L_s" title="\huge L = L_t - L_s" />

Donde:

Lt es el nivel de presión sonora de la banda f que contiene el tono puro;

Ls es la media de los niveles de las dos bandas situadas inmediatamente por encima y
por debajo de f.

Se determina la presencia o ausencia de componentes tonales, entre 20 a 125 Hz:

- Si L < 8 dB(A), no hay componentes tonales.
- Si 8 dB(A) ≤ L ≤ 12 dB(A), hay componente tonal neto.
- Si L > 12 dB(A), hay componente tonal fuerte.

Se determina la presencia o ausencia de componentes tonales, entre 160 a 400 Hz:

- Si L < 5 dB(A), no hay componentes tonale s.
- Si 5 dB(A) ≤ L ≤ 8 dB(A), hay componente tonal neto.
- Si L > 8 dB(A), hay componente tonal fuerte.

Se determina la presencia o ausencia de componentes tonales a partir de 500 Hz:

- Si L < 3 dB(A), no hay componentes tonales.
- Si 3 dB(A) ≤ L ≤ 5 dB(A), hay componente tonal neto.
- Si L > 5 dB(A), hay componente tonal fuerte.

6. El ruido que se evalúa tiene componentes impulsivos si se perciben sonidos de alto
nivel de presión sonora y duración corta. Para evaluar de manera detallada la presencia
de componentes impulsivos se establece el siguiente procedimiento:

Para una determinada fase de ruido de duración Ti en la cual se percibe un ruido
impulsivo:

- Se mide el nivel de presión sonora continuo equivalente ponderado A, durante Ti, LA,
Ti.
- Se mide el nivel de presión sonora ponderado A, determinado con la característica
temporal Impulso (Impulse; en ingles), promediado en el tiempo Ti, LAI.
- Se calcula la diferencia Li = LAI - LA,TI.
- Si LI < 3 dB(A), no hay componentes impulsivos.
- Si 3 dB(A) ≤ LI ≤ 6 dB(A), hay percepción neta de componentes impulsivos.
- Si LI > 6 dB(A), hay percepción fuerte de componentes impulsivos.


# Anexo 3

## Procedimientos de medicion

### Capitulo I procedimiento de medicion para emisiones de ruido

a) La determinación del nivel de presión sonora se realiza y expresa en decibeles
corregidos por frecuencia conforme a la curva de ponderación normalizada tipo A dB(A).

b) Las medidas de los niveles de emisión de ruido a través de los paramentos verticales
de una edificación, cuando las fuentes emisoras de ruido (no importa cuantas) están
ubicadas en el interior o en las fachadas de la edificación, tales como ventiladores,
aparatos de aire acondicionado, rejillas de ventilación, se realizan a 1,5 metros de la
fachada de éstas y a 1,20 metros a partir del nivel mínimo donde se encuentre instalada
la fuente (piso, patas o soporte de la fuente). Siempre se elige la posición, hora y
condiciones de mayor incidencia sonora. Las medidas se efectúan sin modificar las
posiciones habituales de operación de abierto o cerrado de puertas y ventanas y con las
fuentes de ruido en operación habitual.

El sitio de medida se elige efectuando una evaluación previa de la situación de emisión
de ruido por medio de un barrido rápido del nivel de ruido emitido, el cual se hace a 1,5
m de la fachada, de esta manera se determina el punto de mayor nivel sonoro el cual se
toma el sitio de medición, coincidiendo generalmente frente a puertas o ventanas.
En caso de que las fuentes ruidosas estén situadas en azoteas de edificaciones, la
medición se realiza a nivel del límite de la azotea o pretil de ésta. El micrófono se sitúa
a 1,20 metros de altura y si existe pretil o antepecho, a 1,20 metros por encima del
mismo.

Cuando no existen límites medianeros o división parcelaria alguna, porque la actividad o
fuente generadora de ruido se encuentra instalada en zona de espacio público, la
medición se realiza en el límite del área asignada en la correspondiente autorización o
licencia y en su defecto, se mide a 1,5 metros de distancia de la actividad o fuente
generadora de ruido y a 1,20 m del piso.

c) Para la medición de los ruidos residuales, nivel percentil L90 y los ruidos procedentes
de la actividad o fuente(s) origen del ruido y con el fin de prevenir posibles errores de
medición se adoptan las siguientes medidas:

- El micrófono siempre se protege con pantalla antiviento y se coloca sobre un
trípode a la altura definida.
- Se mide la velocidad del viento y si ésta es superior a 3 m/s, se procede de
acuerdo con el parágrafo del Artículo 20.

d) Se deben realizar dos (2) procesos de medición de al menos quince (15) minutos
cada uno, como se especifica en el Artículo 5 de esta resolución; uno con la(s) fuente(s)
ruidosa(s) funcionando durante el período de tiempo de mayor emisión o incidencia,
para obtener el nivel de presión sonora continuo equivalente ponderado A, LAeq,1h, el
cual se corregirá para obtener el nivel de emisión total LRAeq,1h y otro sin la(s) fuente(s)
funcionando, para determinar el ruido residual, el cual también se debe corregir o
ajustar para obtener el LRAeq,1h, Residual.


Teniendo en cuenta la importancia que en la evaluación de estos problemas de ruido
tiene el ruido residual, en caso de no poder definir con claridad los períodos de menor
ruido residual, se deben considerar los comprendidos entre las 01:00 y las 05:00 horas
del día, en caso que la actividad tenga un funcionamiento en período nocturno. En otras
circunstancias, se selecciona el período de tiempo más significativo y si no es posible
medir el ruido residual, se toma el nivel percentil L90, el cual también debe corregirse o
ajustarse.

e) El ruido residual (nivel de presión sonora continuo equivalente corregido ponderado
A, LRAeq,1h, Residual) se mide con la(s) fuente(s) específica(s) apagada(s) y en el mismo
sitio de la medición anterior, manteniendo invariables los condicionantes del entorno y
durante el tiempo y forma estipulado en el Artículo 5 de ésta resolución y se corrige o
ajusta de manera similar a como se corrigen los niveles de emisión total.

f) Si la diferencia aritmética entre LRAeq,1h y LRAeq,1h, Residual es igual o inferior a 3 dB(A),
se deberá indicar que el nivel de ruido de emisión (LRAeq,1h, Residual) es del orden igual o
inferior al ruido residual.

g) La emisión de ruido o aporte de una fuente, de acuerdo con el Artículo 8 de esta
resolución, se calcula por la expresión:

<img src="https://latex.codecogs.com/svg.latex?\inline&space;\huge&space;L_{eq_{emision}}&space;=&space;10\&space;log\&space;(10\&space;^{L_{RAeq,1h}/10}&space;\&space;-&space;\&space;10\&space;^{L_{RAeq,1h,residual}&space;/10})" title="\huge L_{eq_{emision}} = 10\ log\ (10\ ^{L_{RAeq,1h}/10} \ - \ 10\ ^{L_{RAeq,1h,residual} /10})" />

h) Para corregir los niveles equivalentes de emisión total y residual por tonos y por
impulsividad se debe proceder como se especifica en el Anexo 2.

i) Para desarrollar las mediciones, el respectivo sonómetro se debe ajustar o calibrar de
acuerdo con las instrucciones del fabricante utilizando el calibrador o pistófono. Este
procedimiento se debe ejecutar antes y después de efectuar las mediciones.

Se debe definir la naturaleza del ruido: continuo, intermitente, impulsivo, existencia de
tono puro, impulsividad, entre otros.

Asegurarse que el sitio de medición corresponde con el que requiere la evaluación.

Instalar el sonómetro en el trípode de tal manera que el micrófono esté orientado en la
dirección de la(s) fuente(s) específica(s) y localizado como se especifica en el literal b
anterior. Si la localización no es posible, el micrófono se ubicará en la máxima distancia
horizontal, inferior a la estipulada y se efectuará la respectiva anotación y las causas
que originan dicha situación.

En el sitio de medición, en lo posible, únicamente debe estar el técnico que ejecuta las
mediciones, de lo contrario es recomendable que haya el mínimo de personas, las
cuales deben estar lo más separadas del instrumento de medida.

El número mínimo de mediciones a ejecutar es 1 (uno), el cual consta de dos (2)
procesos de medición como se especifica en el literal d, en el horario diurno o nocturno
requerido, determinando en cada una como mínimo los parámetros definidos en esta
resolución.

No se efectúan mediciones con presencia de lluvia y si se llegaren a efectuar, sus
resultados no son tenidos en cuenta.

## Capitulo II Procedimiento de medicion para ruido ambiental

a) La determinación del nivel de presión sonora continuo equivalente, se realiza y
expresa en decibeles corregidos por frecuencia conforme a la curva de ponderación
normalizada tipo A (dB(A)).

b) Las medidas de niveles de ruido ambiental con ponderación A, se efectúan teniendo
en consideración la norma ISO 1996 o aquella norma que la adicione, modifique o
sustituya.

c) En las zonas urbanas y de expansión urbana, el ruido ambiental se mide instalando
el micrófono a una altura de cuatro (4) metros medidos a partir del suelo terrestre y a
una distancia equidistante de las fachadas, barreras o muros existentes a ambos lados
del punto de medición, si estos no existen en uno de los costados, el punto se sitúa a
una distancia de cuatro (4) metros medidos horizontalmente desde el costado que las
posea, si no existen en ninguno de los costados, se toma el punto equidistante entre los
límites del espacio público correspondiente. Bajo ninguna circunstancia se pueden
efectuar mediciones bajo puentes o estructuras similares.

Cada medición con la distribución efectuada en los quince (15) minutos, según se
estipula en el Artículo 5 de esta resolución, debe constar de cinco (5) mediciones
parciales distribuidas en tiempos iguales, cada una de las cuales debe tener una
posición orientada del micrófono, así: Norte, Sur, Este, Oeste y Vertical hacia arriba. El
resultado de la medición es obtenido mediante la siguiente expresión:


<img src="https://latex.codecogs.com/svg.latex?\inline&space;\huge&space;L_{Aeq}&space;=&space;10\&space;log&space;\left&space;[&space;\frac{1}{5}(10^{L_N/10}&space;&plus;&space;10^{L_O/10}&space;&plus;&space;10^{L_S/10}&space;&plus;&space;10^{L_E/10}&space;&plus;&space;10^{L_V/10}&space;\right&space;]" title="\huge L_{Aeq} = 10\ log \left [ \frac{1}{5}(10^{L_N/10} + 10^{L_O/10} + 10^{L_S/10} + 10^{L_E/10} + 10^{L_V/10} \right ]" />


Donde:

LAeq = Nivel equivalente resultante de la medición.

LN = Nivel equivalente medido en la posición del micrófono orientada en sentido norte

LO = Nivel equivalente medido en la posición del micrófono orientada en sentido oeste

LS = Nivel equivalente medido en la posición del micrófono orientada en sentido sur

LE = Nivel equivalente medido en la posición del micrófono orientada en sentido este

LV = Nivel equivalente medido en la posición del micrófono orientada en sentido vertical

En el respectivo informe de resultados se debe especificar claramente la altura y
distancia horizontal de las mediciones, de tal manera que permitan la repetibilidad de
las mismas en el futuro.

d) Para la medición de los ruidos ambientales, residuales o procedentes de fuentes
específicas para aspectos ambientales y con el fin de prevenir posibles errores de
medición se adoptan las siguientes medidas:

El micrófono siempre se debe proteger con la pantalla antiviento y se coloca sobre un
trípode o dispositivo adecuado para su montaje, a la altura definida.

Se mide la velocidad del viento y si ésta es superior a 3 m/s, se procede de acuerdo con
el siguiente parágrafo.

*La velocidad del viento se debe medir utilizando un anemómetro o un
dispositivo medidor de velocidad del viento, si está es mayor a tres metros por segundo
(3 m/s), se debe utilizar una pantalla antiviento adecuada de acuerdo con la velocidad
del viento medida, y aplicar la respectiva corrección de acuerdo con las curvas de
respuesta que el fabricante de las pantallas antiviento y micrófonos suministra.*

No se deben desarrollar mediciones en condiciones de lluvia, de pavimentos húmedos
cuando se esté en cercanías o sobre vías de transito vehicular.

e) Para corregir los niveles equivalentes por tonos y por impulsividad se debe proceder
como se especifica en el Anexo 2 de esta Resolución.

f) Para desarrollar las mediciones, el respectivo sonómetro se debe ajustar o calibrar
de acuerdo con las instrucciones del fabricante utilizando el calibrador o pistófono. Este
procedimiento se debe ejecutar antes y después de efectuar las mediciones.

g) Si por alguna razón se desea estimar el aporte que cualquier fuente específica hace
al ambiente, se procede de la siguiente manera: con la fuente específica en
funcionamiento se efectúa una medición de ruido ambiental a cuatro (4) metros de
altura y a una distancia de tres (3) a cuatro (4) metros de la fuente en sentido horizontal,
instalando el medidor de sonido frente a la fuente y procediendo de acuerdo con lo
estipulado en este anexo para obtener una medida en una hora diurna o nocturna
según el caso, luego se determina el ruido residual correspondiente, los resultados se
corrigen y se restan logarítmicamente, obteniéndose así el aporte que la fuente hace al
medio ambiente.


## Capitulo III Procedimiento para determinacion del numero de puntos y de los tiempos de medicion para ruido ambiental


Para la determinación del número de puntos y de los tiempos de medición se
recomienda aplicar la siguiente metodología:

Definir claramente los objetivos del estudio.

Realizar un estudio y evaluación rápida de la(s) ciudad(es) y de la(s) zona(s) a estudiar.

Determinar las áreas donde se deben hacer las mediciones.

Establecer una grilla o retícula sobre estos sectores.

Determinar las distancias máximas para ubicación de sitios de medida.

Ubicar los sitios de medida.

Establecer el número de horas diurnas y nocturnas durante las cuales se efectúa la
toma de mediciones.

Establecer los horarios de medición.

Establecer el número de días por semana y el número de semanas por mes durante las
cuales se efectúan las mediciones.

Determinar el número de meses al año durante los cuales se desarrollan mediciones.

Establecer otras actividades a desarrollar simultáneamente con la tarea de mediciones.

### Definir claramente los objetivos del estudio

La autoridad ambiental correspondiente debe especificar claramente los objetivos que
motivan la realización del estudio a ejecutar.

Para la determinación de estos objetivos es necesario tener en cuenta que el objetivo
final del estudio no es la realización de uno o varios mapas, esto es solo una
herramienta que aporta al buen desarrollo, logro y éxito del proyecto para el cual se
efectúa el estudio.

Para la determinación de los objetivos se debe tener en cuenta, de una manera muy
especial, el alcance, el objeto y el artículo 23 de esta resolución. Para el logro de estos
objetivos se debe incluir la realización de los mapas de ruido de las zonas de interés,
como un instrumento que permite visualizar e l estado ambiental de contaminación por
ruido y proyectar soluciones a las problemáticas generales encontradas,.

### Realizar un estudio y evaluación rápidos de la(s) ciudad(es) y de la(s) zona(s) o area(s) a estudiar.

La autoridad ambiental es la encargada de efectuar un estudio y evaluación rápida
sobre la situación general en que se encuentra la respectiva ciudad en cuanto se refiere
a la contaminación por ruido, partiendo de la respectiva distribución de usos del suelo,
de los planes de ordenamiento territorial existentes, de la sectorización y
subsectorización establecida en la Tabla 2 de esta resolución, así como de las
tendencias, costumbres y polos de desarrollo que presente la respectiva ciudad o área
en consideración. Este estudio y evaluación rápida se efectuará inicialmente sobre
cartografía actualizada existente y luego se debe corroborar por medio de un recorrido
de observación y comprobación.

Con base en el estudio y evaluación rápidos se identifican posibles zonas y sectores
que posean problemas por contaminación ambiental de ruido, o así no los tengan,
presenten alguna característica especial de interés en lo que respecta a ruido, estas
zonas o sectores tienen que ser tenidos en cuenta al momento de determinar los sitios
donde se deben hacer las mediciones.

### Determinar las áreas donde se deben hacer las mediciones.

Para la determinación de las áreas donde se deben hacer las mediciones es necesario,
tener en cuenta la Tabla 2 de esta resolución con el fin de cubrir todos los sectores y
subsectores en ella establecidos; en caso de ser necesario.

Con base en lo anterior, las autoridades ambientales establecerán las áreas donde
deben efectuar las mediciones de ruido para desarrollar los respectivos mapas que
muestren el estado actual de la incidencia del ruido en el medio ambiente. Además de
los usos del suelo y de las actividades desarrolladas, es necesario tener muy presente
las características generales de cada área, como por ejemplo densidades
poblacionales, densidades de trafico, densidades de comercio, densidades o
aglomeraciones industriales, densidades de edificaciones, horas del día y/o de la noche
de mayores y menores actividades, en forma similar para los diferentes días de la
semana, las diferentes semanas del mes, los diferentes meses del año y las respectivas
temporadas en las cuales se efectúen ciertas actividades que solo ocurren en esas
temporadas.

Una vez efectuada la selección, con sus respectivas justificaciones, de las áreas donde
se deben desarrollar las mediciones es necesario determinar en que sitios se hacen las
mismas.

### Establecer una grilla o retícula sobre estos sectores

Sobre cada una de las áreas seleccionadas se establecen los usos permitidos del
suelo, y teniendo en cuenta estos límites se hace una retícula o grilla cuyo
espaciamiento de vértices será definido por la autoridad competente de acuerdo con las
consideraciones efectuadas en el titulo anterior sobre características generales de cada
área.

Se sugiere que para sectores rurales donde hay ausencia de instalaciones o no hay
asentamientos humanos, estas grillas se hagan con distancias entre 3 y 5 Km. como
máximo entre vértices, en áreas donde se presentan grandes aglomeraciones de
personas y/o de fuentes de ruido se aconseja hacer retículas de lados pequeños,
máximo 250 m y en los demás sitios se sugiere como máximo 1000 m.

### Determinar las distancias máximas para ubicación de sitios de medida

Establecida la respectiva grilla en cada sector, y analizando las actividades que en ella
se desarrollan y su comportamiento en lo que respecta a la generación de ruido, la
autoridad competente determina cada cuantos vértices de la grilla se deben fijar los
respectivos sitios para la toma de medidas y cual de ellos es el punto de inicio o marco
de referencia para determinar los demás.

No obstante, si existe(n) algún(os) punto(s) que no esté(n) en los vértices de la grilla y
que por alguna razón requiera(n) ser evaluado(s) y medido(s), se inserta(n) dentro de
los puntos a medir y se continua con el respectivo proceso dentro de este
procedimiento.

### Ubicar los sitios de medida

Habiendo determinado, sobre la retícula, cuales son los puntos donde se debe tomar
las mediciones, es necesario ubicar el sitio de medida, de tal manera que pueda ser
relocalizado nuevamente con exactitud para efectos de tomar nuevas mediciones o de
tener que corroborar datos.

Para lograr esto, se debe hacer un recorrido real, analizar el área alrededor del punto
determinado en la grilla y ubicar un sitio seguro que cumpla con lo especificado en esta
resolución en cuanto a distancias y ubicación respecto de fachadas, y que además
presente características óptimas para efectuar las mediciones y brinde seguridad para
quienes desarrollan la labor de campo.

Los sitios de medición no necesariamente deben ubicarse sobre cruces viales, pueden
establecerse en sitios distintos siempre que cumplan con los requisitos establecidos en
esta resolución.

Una vez determinado el punto físico, se recomienda georeferenciarlo y describirlo
físicamente, para luego poder localizarlo, reconocerlo, identificarlo y ubicarlo con toda
exactitud en el momento de efectuar las mediciones y luego cuando se requiera para
las posteriores revisiones y actualizaciones.

### Establecer el número de horas diurnas y nocturnas durante las cuales se efectúa la toma de mediciones.

De acuerdo con las consideraciones y motivaciones que las autoridades ambientales
han tenido en cuenta para determinar las áreas donde se deben hacer las mediciones,
con los criterios para la selección y ubicación de sitios de medida, con la fluctuación
durante el período diurno y nocturno de las actividades que generen o no ruido, las
autoridades ambientales establecen los períodos de máxima y de mínima emisión de
ruido (recordar que el parámetro de medida Leq es un promedio del ruido donde se
incluyen tanto los periodos de máxima, como los intermedios y los de mínima
generación de ruido) y con base en ellos determinan para cada sitio de medida el
número de horas que en cada período diurno y nocturno deben efectuar mediciones y
con estos resultados establecen los respectivos LAReq,d y LAReq,n, para el día de
medición. El número de horas de medición por período diurno o nocturno, en cada sitio,
no debe ser inferior a 2.

### Establecer los horarios de medición

Con los puntos determinados, con los sitios de medición localizados, con el numero de
horas diarias a medir, es necesario que las autoridades ambiéntales determinen los
horarios en los cuales se efectúan las mediciones en cada punto, se recomienda no
hacer mediciones de mas de una hora continua en cada punto, a menos que se haya
determinado mas de 7 horas diurnas o 5 nocturnas por día o noche respectivamente.

### Establecer el número de días por semana y el numero de semanas por mes durante los cuales se efectúan las mediciones

El numero mínimo de días a la semana en los cuales se efectúen las mediciones es de
dos (2), uno de ellos tiene que ser un domingo, y el número mínimo de semanas por
mes a medir es una (1), sin embargo las consideraciones efectuadas para determinar
las áreas donde se deben hacer las mediciones dan la base fundamental sobre la cual
las autoridades ambientales determinen estos dos parámetros.

### Determinar el número de meses al año durante los cuales se desarrollan las mediciones.

El intervalo de largo plazo que esta resolución ha determinado es de un año, por lo
tanto las autoridades ambientales deben determinar, para cada punto, el número de
meses y los meses en los cuales, durante el año, se deben tomar las mediciones. Esta
determinación obedece a los diferentes tipos de actividades, ciclos, períodos de
operación o funcionamiento, estados de máxima y mínima actividad, temporadas, entre
otros, que se den dentro del respectivo año.

### Establecer otras actividades a desarrollar simultáneamente con la tarea de mediciones.

Se recomienda que durante el proceso de planificación de las mediciones, las
autoridades ambientales programen otro tipo de actividades que los encargados de
efectuar las mediciones pueden ejecutar simultáneamente con esta actividad y que
coadyuven a mejorar y clarificar la información recolectada.

Tales actividades pueden contemplar la realización de encuestas a la población
residente, la recolección de información geográfica, la recolección de información
relacionada con posibles focos generadores de ruido, fuentes de ruido, tipos de tráfico,
variaciones de tráfico, épocas más ruidosas durante el día o la noche, en períodos
laborables o festivos, medidas que pueden mejorar el problema de ruido, u otro tipo de
actividades en los respectivos sectores y que tengan relación directa con la generación
y los efectos del ruido, entre otros muchos aspectos.

Así mismo pueden programar actividades de recolección de información
complementaria como son datos poblacionales, centros educativos, hospitales,
instituciones, tipo de industrias, tipo de vías, centros de recreación y de espectáculos,
datos de trafico y parque automotor, carreteras, parqueaderos, negocios, tipos de
horarios de operación, cercanías a zonas muy ruidosas como por ejemplo aeropuertos,
obras, terminales de transportes, denuncias por contaminación por ruido y acciones a
las que dieron lugar.

### Medición de los niveles de ruido

Con la determinación de sitios, tiempos de medida diarios, semanales, mensuales y
anuales, se establece el cronograma para la medición de los niveles de ruido en todos y
cada uno de los sitios de medición y se determinan las fechas de inicio de las
mediciones.

### Presentación de resultados para cada punto de medida

Los resultados de las medidas se deben presentar para cada punto en la forma como
se estipula en esta resolución, es decir los Niveles corregidos de presión sonora
continuo equivalente ponderados A, LRAeq,T, diurno y nocturno, los Niveles corregidos de
presión sonora continuo equivalente ponderados A residuales LRAeq,T, Residual diurnos y
nocturnos.

Estos valores se deben, además, presentar para cada hora, día, semana, mes y año de
medición en cada sitio de medida georeferenciado que la autoridad ambiental ha
determinado.



