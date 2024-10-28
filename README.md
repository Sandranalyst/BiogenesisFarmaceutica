Este proyecto tiene como propósito identificar las ubicaciones óptimas para la expansión de laboratorios farmacéuticos, basándose en el análisis de datos de incidencia de covid-19, tasas de vacunación y la disponibilidad de estructuras sanitarias.  
Entre los objetivos organizacionales está optimizar la respuesta a los efectos de la pandemia y post pandemia, con el fin de mejorar el acceso a las vacunas.
Este estudio tiene el objetivo de ayudar a esta empresa en su estrategia de expansión en América Latina, por lo cual necesita ubicar regiones y recolectar datos relevantes para la toma de decisiones informadas.
Para lograr este objetivo se debe evaluar la demanda de vacunas, la logística de su distribución y la infraestructura sanitaria existente.

PARTE UNO: CARGA Y TRANSFORMACIÓN DE DATOS: Se trabajó con un dataset llamado data_latinoamerica.csv que inicialmente tenía 12.216.057 filas y 50 columnas y el archivo readme.txt que contiene el diccionario de los datos. 
Se hace un filtrado de los datos por países seleccionados y fechas posteriores a enero de 2021 y se Se guarda en la variable: data_Latinoamerica_paises_fecha. 
También se hace un relleno de los valores faltantes utilizando el promedio de los valores por cada columna.
Después del proceso de limpieza quedan 3.744 filas y 50 columnas y se procede a guardar el archivo como DatosFinalesFiltrado.csv. en la carpeta proyecto_integrador.
Se calcularon estadísticas principales columna por columna como la media, varianza y rango desviación estándar y percentiles , utilizando el ciclo for.

PARTE 2: ANÁLISIS EXPLORATORIO - VISUALIZACIÓN 
Se calculan medidas estadísticas con Pandas y Numpy, como tendencia central, dispersión y correlaciones entre variables. Primero se importan las librerías Panda y Numpy y haciendo un ciclo for columna por columna del dataframe data_latinoamerica_paises se pueden mirar las estadísticas básicas como la media, la mediana, desviación estándar, mínimo y máximo de cada columna.
Se crean visualizaciones con Matplotlib y Seaborn. Se generan gráficos como histogramas, gráficos de barras, mapas de calor y diagramas de dispersión para comprender la distribución de la incidencia del Covid-19, las tasas de vacunación y exploran posibles relaciones entre variables. 

TERCERA PARTE: Se hace un análisis exploratorio utilizando técnicas avanzadas de Numpy y Pandas, centradas en las series temporales para comprender la evolución de elementos específicos del conjunto de datos. 

CUARTA PARTE:  Creacion de  dashboard interactivo, utilizarán los datos proporcionados para ofrecer insights valiosos sobre posibles ubicaciones estratégicas para futuros laboratorios y centros de vacunación. Este análisis de tendencias y demografía será fundamental para comprender el entorno del mercado en los países de interés.

Respuesta Principal del Proyecto: Ubicaciones Óptimas para la Expansión de Laboratorios Farmacéuticos
A partir del análisis, las ubicaciones óptimas para la expansión de laboratorios farmacéuticos son:
Perú y México: Como los países más afectados por la pandemia y con un alto número de fallecidos en relación con sus casos y población, requieren mayor inversión en infraestructuras sanitarias y apoyo farmacéutico. Estos países son claros candidatos para la expansión de laboratorios, dado su mercado potencial y la necesidad urgente de mejorar su respuesta sanitaria.
Chile: Aunque su tasa de mortalidad fue la más baja, Chile presenta una infraestructura sanitaria avanzada y un alto nivel de vacunación, lo que lo convierte en un país clave para la instalación de laboratorios que puedan atender eficientemente las demandas de la región.
Brasil: A pesar de su menor número de fallecidos relativos a la población, Brasil, por su gran tamaño y problemas en la gestión de la vacunación, es un mercado importante que puede beneficiarse de una mayor inversión en el sector farmacéutico.
En resumen, Perú, México, Chile y Brasil representan ubicaciones estratégicas para la expansión de laboratorios farmacéuticos en América Latina, atendiendo tanto a la necesidad sanitaria como al potencial de mercado.



