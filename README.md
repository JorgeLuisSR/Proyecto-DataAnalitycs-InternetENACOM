# DataAnalitycs - Internet - ENACOM
## Sobre el proyecto
En este proyecto, tomo el papel de un analista de datos al servicio de la empresa **ENACOM** (Argentina) o alguna empresa de telecomunicaciones que pueda ser representada a partir de los datos abiertos que **ENACOM** provée, en el proyecto se presentan procesos de EDA y se incluye un Dashboard interactivo con **Streamlit**.
## Introducción
En el ambito de las *telecomunicaciones*, y más precisamente del acceso a servicios de **Internet**, se inicia a partir del set de datos **Internet.xlsx** que la empresa provee, de allí extraemos la información que se recopila sobre los accesos a internet, el tipo de tecnología con el cual se accede, los periodos en los que se accede, y las velocidades de conexión que se brinda en ese momento. 

La empresa ubica estos datos en un set de hojas de Excel (encontrado en la página oficial) de la cúal utilizaremos solo aquellas que nos sirva para generar conclusiones de utilidad para la empresa.

En este proyecto se encuentra un Notebook de Jupiter **(EDA.ipynb)** en donde se desarrolla y detalla el proceso de análisis exploratorio de datos realizado para encontrar patrones y desarrollar insights sobre los conjuntos de datos de interés.

En la carpeta **/datasets** de este mismo proyecto se ubica el archivo ***internet.xlsx*** original extraído de la web oficial de ENACOM, y además se encuentra un conjunto de archivos ***.csv*** que incluyen los datos extraídos a partir del EDA con el objetivo de reducir la necesidad de cálculos para el dashboard.

Durante el proceso de análisis exploratorio de datos se desarrollaron unos **kpis** relevantes que nos sirven para determinar el desempeño de la empresa hacia determinados objetivos, principalmente en cuanto a extensión de tecnologías modernas, adquisición de clientes y mejora en calidades de servicio de forma estratégica.

## EDA
Durante este proceso se realiza una limpieza de los datos, suficiente como para permitir realizar cálculos y visualizaciones sobre los mismos, esto incluye prevención de duplicados, eliminación de datos o registros incompletos, nulos o aparentemente erroneos, cálculo de índices únicos numéricos, agregación de datos y normalización o estandarización de datos de carácter cualitativo.
Es en este proceso que se empieza a graficar variables de posible interés con el objetivo de encontrar patrones significativos o tendencias relevantes, es por este proceso por el cual se pudo identificar de forma visual la creciente adaptación de tecnologías como fibra óptica o la importancia en el histórico de la empresa de las tecnologías de cablemódem, así como poder ver las metricas par cada provincia inidividualmente

### Datasets 
* ***Internet.xlsx***: Set de datos originales
* ***\*.csv***: Conjuntos de sets de datos limpios y agregados con información dedicada al Dashboard

## KPIs
Cada uno de los KPIs aqui surgen del analisis en ***EDA.ipynb***, donde se encuentran justificados y detallados
<div style="text-align: center;"> <i>KPI 1 : Incremento porcentual de nuevas tecnologias <br/><b>Incrementar en un 1,5% el uso de tecnologías de alta velocidad en comparación al trimestre anterior</b></i></div><br/>

<div style="text-align: center;"> <i>KPI 2 : Incremento provincial de accesos por cada 100 hogares <br/><b>Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia.</b></i></div><br/>

<div style="text-align: center;"> <i>KPI 3 : Incremento provincial estrategico de velocidad media de conección<br/><b>Aumentar la velocidad media de internet en al menos un 10% en las provincias con velocidades por debajo del promedio nacional en relación al trimestre anterior.</b></i></div><br/>
