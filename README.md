# Ciencia de Datos
Material y Cuadernos de GoogleColab sobre la electiva Ciencia de datos
## ¿Qué es la Ciencia de Datos?
La ciencia de datos es un campo que usa tecnicas de aprendizaje automatico y la estadistíca para analizar, interpretar y obtener conocimineto valioso a partir de los datos, este campo se encuentra en la intersección de tres areas principales, **Conocimiento de dominio** (Experiencia en el area especifica que se esta analizando), **Matemáticas y Estadistica** (Para el analisis y modelado de datos y **Ciencias de la computación** (Para el procesamiento y manejo de grandes volumnenes de datos.)
La combinación de estas tres áreas permite la extracción de conocimiento e insights valiosos a partir de los datos.

<img width="640" height="707" alt="image" src="https://github.com/user-attachments/assets/4cf4f840-cf08-400b-afe1-801207f12ca9" />

### Relacion entre la IA, el Machine Learning (ML) y la Ciencia de Datos.
1. La IA busca crear sistemas capaces de realizar tareas que requieran inteligencia humana.
2. Dentro de la IA, el *Aprendizaje automatico (Machine Learning - ML)* se enfoca en desarrollar algoritmos que permiten a las computadoras aprender de los datos sin ser programadas explicitamente.
3. La Ciencia de Datos es un campo que usa metodos, procesos y algoritmos cientificos para extraer conocimientos *e insights* a partir de grandes volumenes de datos, apoyandose en diversas tecnicas, herramientas estadisticas y de vvisualización para lograr sus objetivos.
*En esencia, el ML es una herramienta clave dentro de la IA y la Ciencia de Datos, este campo es el que aplica estas y otras herramientas para la comprension y la toma de desiciones basda en los datos*
## Diversos tipos de Ciencia de Datos.
<img width="1170" height="674" alt="image" src="https://github.com/user-attachments/assets/d0069f67-91f8-4916-89d9-3627edc02cc3" />

## Tareas regulares de la Ciencia de Datos.
1. Analisis de datos
* ¿Que porcentaje de ususarios vuelvena nuestro sitio?
* ¿Que productos se suelen comprar juntos?
2. Modelado/Estadisticas
* ¿Cuantos coches vamos a vender el año que viene?
* ¿Que ciudad es mejor para abrir una nueva oficiona?
3. Ingenieria/Prototipado
* Producto para utilizar un modelo de prediccion
* Visualizacion de analisis

## Tareas de Aprendizaje Automático

### Clasificación:
Predice a qué clase pertenece un dato.
* Ejemplos: Agrupar clientes, asignar votantes.
* Algoritmos comunes: Árboles de decisión, redes neuronales, K vecinos más cercanos.

### Regresión:
Predice valores numéricos.
* Ejemplos: Tasa de desempleo, prima de seguros.
* Algoritmos: Regresión lineal, regresión logística.

### Detección de anomalías:
Identifica valores atípicos en un conjunto de datos.
* Ejemplos: Fraudes en tarjetas de crédito, detección de intrusiones.
* Algoritmos: Basado en distancia, densidad, LOF.

### Series temporales:
Predice valores futuros según datos históricos.
* Ejemplos: Previsión de ventas o producción.
* Algoritmos: Suavizado exponencial, ARIMA, regresión.

### Clustering:
Encuentra grupos naturales de datos según sus propiedades.
* Ejemplos: Segmentación de clientes.
* Algoritmos: K-means, DBSCAN.

### Análisis de asociación:
Detecta relaciones entre elementos en transacciones.
* Ejemplos: Ventas cruzadas en minoristas.
* Algoritmos: FP Growth, Apriori.
  
## Python para el Análisis de datos.
### Bibliotecas de python para ciencia de datos.
Cajas de herramientas populares de python.
* **Numpy:**
  Introducen objetos para matrices y matrices multidimensionales, asi como funciones que permiten realizar operaciones matematicas y estadisticas avanzadas sobre esos objetos.
* **SciPy:**
  Colección de algoritmos para álgebra lineal, ecuaciones diferenciales, integracion numerica, optimizacion, estadistica y mas.
* **Pandas:**
  Agrega estruturas de datos y herramientas diseñadas para trabajar con datos similiares a tablas( Similares a Series y Data Frames en R) ademas proporciona herramientas para la manipulacion de   datos: Remodelacion, Fusión, Clasificación, Segmentacion, Agregacion, etc...
* **Scikit-Learn:**
  Propone algoritmos de aprendizaje automatico: Clasificación, Regresión, Agrupación, Validacion de modelos, etc...
### Bibliotecas de visualización.
* **matplotlib:**
  Biblioteca de trazado 2D de python que produce cifras de calidad de publicacion en una variedad de formatos precisos con un conjunto de funcionalidades similares a las de MATLAB como: Graficos   de lineas, Diagramas de dispersión, Graficos de barras, Histogramas, Graficos circulares, etc
* **Seaborn:**
  Basado en **matpolib** proporciona una interfaz de alto nivel para dibua¿jar graficas estadisticos atractivos

## El proceso de la Ciencia de datos

### Modelo CRISP-DM
Ciclo de vida CRISP-DM (Cross-Industry Standard Process for Data Mining) un modelo metodologico para proyectos de mineria de datos y ciencia de datos. Consta de seis fases: **Comprensión del negocio** (entender los objetivos del proyecto desde una perspectiva empresarial), **Comprensioón de los datos** (Familiarizarse con los datos disponibles), **Preparación de los datos** (limpieza y transformacion de los datos), **Modelado** (Selección  y aplicación de las tecnicas del modelado) **Evaluación** (Valorar el modelo en funcion de los objetivos del negocio) y **Despliegue** (Integrar el odelo en el entorno opertativo).

<img width="576" height="671" alt="image" src="https://github.com/user-attachments/assets/9919b4e0-7a10-428c-9b48-3b236a3ca037" />

**Las flechas indican el flujo entre las fases, destacando la naturaleza iterativa del proceso donde se puede regresar a fases anteriores segun los resultados obtenidos.**

* **Fase 1: Comprensión del Negocio:**
Se define el objetivo del proyecto desde la perspectiva del negocio, los problemas que se quieren resolver y los criterios de éxito.

* **Fase 2: Comprensión de los datos:**
Se recolectan los datos iniciales, se analizan, se identifican problemas de calidad y se obtienen primeras conclusiones.

* **Fase 3: Preparación de los datos:**
Se limpian, transforman, integran y seleccionan los datos que se usarán para el modelado. Es una de las fases más largas.

* **Fase 4: Modelado:**
Se aplican técnicas estadísticas, de machine learning o minería de datos para construir modelos predictivos o descriptivos.
  
* **Fase 5: Evaluación:**
Se revisan los resultados del modelo y se evalúa si cumplen con los objetivos definidos en la fase de negocio.
  
* **Fase 6: Despliegue:**
Se implementa el modelo en un entorno real (por ejemplo, en un sistema de producción) y se planifica su monitoreo y mantenimiento.

### Flujo de trabajo del aprendizaje automático.

El flujo del trabajo se refiere a las etapas involucradas en el proceso de creación de un sistema de aprendizaje automático exitoso.

<img width="763" height="476" alt="image" src="https://github.com/user-attachments/assets/f1fd4c81-0147-4f48-84cd-cfb887459064" />

### Proposito e Importancia del Flujo de trabajo de ML.

El flujo de trabajo sirve como una hoja de ruta para construir sistemas de ML efectivos, asegurar que cada etapa se realice metódicamente conduce a modelos confiables y precisos. Por esto es crucial para la construccion de sistemas efectivos, porque proporciona una estructura, reduce errores y garantiza modelos probados y listos para su aplicación en el mundo real.

* **Definición del problema:**
Se plantea el objetivo: qué se quiere predecir, clasificar o estimar. Aquí se define si el problema es de clasificación, regresión, clustering, etc.

* **Recolección de datos:**
Se obtienen los datos necesarios desde bases de datos, sensores, APIs o archivos. La calidad y cantidad de los datos impacta directamente en el modelo.

* **Exploración y análisis de datos (EDA – Exploratory Data Analysis):**
Se analizan los datos con estadísticas y visualizaciones para entender su distribución, patrones y posibles problemas.

* **Preprocesamiento y preparación de datos:**
Se limpian valores nulos, se codifican variables categóricas, se normalizan o escalan los datos y se dividen en conjunto de entrenamiento, validación y prueba.

* **Selección del modelo y entrenamiento:**
Se elige el algoritmo más adecuado (árboles de decisión, redes neuronales, regresión logística, etc.) y se entrena con los datos.

* **Evaluación del modelo:**
Se mide el rendimiento con métricas (accuracy, precisión, recall, RMSE, etc.) para determinar si el modelo es útil.

* **Optimización y ajuste de hiperparámetros:**
Se mejora el modelo ajustando parámetros y aplicando técnicas como grid search o cross-validation.

* **Despliegue (Deployment):**
Se implementa el modelo en un entorno real (ej. en una app, web service o sistema empresarial).

## Estuctura de un proyecto clasico de Ciencia de Datos.

Un proyecto clasico de ciencia de datos comienza con la preparación de datos, los cuales se limpian y preparan para entrenar un modelo, se evalúa el rendimiento en un conjunto de prueba y, si es aceptable, se implementa; de lo contrario se revisan los pasos anteriores.

<img width="1198" height="477" alt="image" src="https://github.com/user-attachments/assets/cdc49f86-bc5c-45d2-9f96-99205bebd01e" />

### Ciclo de vida de la Ciencia de Datos.

Su ciclo de vida comienza con la creacion de un modelo a partir de datos, pasa por un preoceso de producción, se valida y despliega para su consumo e interacción, se retroalimenta para su monitoreo, actualización y posible optimización.

<img width="850" height="383" alt="image" src="https://github.com/user-attachments/assets/42bd0fde-2194-4890-af31-f2797b6b8f78" />

## Machine Learning

### Definición.

El aprendizaje automatico es una subdisciplina de la Inteligencia Artificial que se centra en el desarrollo de algortimos y modelos estadisticos que permiten a las computadoras aprender de los datos y hacer predicciones o tomar desiciones basadoas en ellos. Con el timepo los sistemas de ML mejoran su rendimiento a medida que se exponen a más datos.

Se centra en el estudio de algortimos que aprender a realizar una tarea a partir de la experiencia previa con datos. Generalmente se refiere a cambios en sistemas que realizan tareas asociadas con IA, como el **recoocimiento, diagnostico, planificación, control de maquinas, predicción, entre otros...**

### Programación tradicional vs Machine Learning

<img width="1045" height="535" alt="image" src="https://github.com/user-attachments/assets/95391301-1b83-4494-8008-6646bf883138" />

### Proceso del Aprendizaje Automático

<img width="1254" height="438" alt="image" src="https://github.com/user-attachments/assets/4a954dcc-2c9a-4e15-a438-b7856e1dc1d0" />
