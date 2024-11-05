# Portafolio Alvarez Luis Ignacio

## Proyecto 1: [Modelo de comestibilidad de los hongos](https://github.com/AlvarezLI/ProjectDS-Mushrooms)  
Este proyecto es parte de mi entrega final para un curso de ciencia de datos, donde clasifiqué diferentes hongos en función de su comestibilidad.

### Fuente del conjunto de datos
El conjunto de datos utilizado en este proyecto es el **conjunto de datos de clasificación de hongos** de Kaggle, que proporciona una descripción completa de las características de los hongos.

### Técnicas de preprocesamiento de datos
Se emplearon varias técnicas de filtrado para preparar los datos, entre ellas:
- **Control de valores nulos**: se garantizó la integridad del conjunto de datos mediante el manejo adecuado de los valores faltantes.
- **Codificación de variables categóricas**: se transformaron las características categóricas en valores numéricos para un entrenamiento eficaz del aprendizaje automático.

### Algoritmos de aprendizaje automático
Se aplicaron los siguientes algoritmos para predecir la comestibilidad de los hongos:
- **Clasificador de bosque aleatorio**
- **Máquina de vectores de soporte (SVM)**
- **Regresión logística**

---

## Proyecto 2: [Modelo de predicción meteorológica](https://github.com/AlvarezLI/ProyectoDSII_ParteI) 
En este proyecto, realicé un análisis profundo de un conjunto de datos sintéticos diseñado para clasificar diferentes tipos de clima.

### Técnicas de preprocesamiento de datos
Se implementaron las siguientes técnicas para preparar los datos:
- **Manejo e imputación de valores nulos**: Se abordaron los valores faltantes para mantener la calidad del conjunto de datos.
- **Codificación de variables categóricas**: Se convirtieron las variables categóricas a un formato adecuado para el entrenamiento del modelo.
- **Eliminación de valores atípicos**: Se aplicó el método de rango intercuartil (RIC) para eliminar los valores atípicos.
  
### Algoritmos de aprendizaje automático
Se implementaron varios algoritmos de clasificación para predecir el tipo de clima, entre ellos:
- **Clasificador de bosque aleatorio**
- **Máquina de refuerzo de gradiente (GBM)**
- **Regresión logística**
- **Clasificador de árbol de decisiones**

### Optimización y evaluación de modelos
Se evaluó cada modelo utilizando métricas clave como:
- **Precisión**: se midió la exactitud general de las predicciones.
- **Matriz de confusión**: se evaluó el rendimiento de los modelos de clasificación.

Se compararon los modelos para identificar el que mejor se ajustaba a la predicción de los tipos de clima y se realizó un **ajuste de hiperparámetros** para mejorar los resultados.

---

## Proyecto 3: [Análisis de Obras Públicas en Excel y Tableau](https://github.com/AlvarezLI/Project_PublicWorks) 

En este proyecto, realicé un análisis exhaustivo de los datos de obras públicas en Argentina, con el objetivo de obtener insights sobre la distribución y el estado de las inversiones en infraestructura a nivel regional, utilizando tanto **Excel** como **Tableau** para optimizar la visualización y el análisis de los datos.

### Fuente del conjunto de datos
El conjunto de datos fue obtenido del **Mapa de Inversiones del Ministerio de Obras Públicas de Argentina**, que proporciona información detallada sobre las obras públicas en distintas provincias y su estado de avance.

### Técnicas de análisis y preprocesamiento de datos
Para procesar y analizar los datos, se utilizaron las siguientes técnicas:

- **Limpieza y validación de datos**: se eliminaron errores y se validaron los valores, tanto cualitativos como cuantitativos, para asegurar la precisión del análisis.
- **Tablas dinámicas**: se emplearon tablas dinámicas en Excel para facilitar la exploración de los datos y obtener respuestas a preguntas clave como la cantidad de obras por tipo, estado y ubicación geográfica.
- **Segmentación de datos**: se añadieron segmentadores para permitir la segmentación dinámica de los datos por categorías, como tipo de obra, año, estado de ejecución y provincia.

### Visualización y dashboards
Para mejorar la interpretación de los datos, se crearon paneles visuales interactivos tanto en **Excel** como en **Tableau**:

- **Dashboard en Excel**: se diseñó un panel interactivo con gráficos y segmentadores que permiten visualizar rápidamente la distribución y el estado de las obras públicas:
  - **Distribución de obras por provincia**: se destacan las provincias con mayor inversión en obras.
  - **Clasificación de obras por estado**: se muestra el progreso de las obras (planificadas, en ejecución, finalizadas).
  - **Análisis por tipo de obra**: se identifican las categorías de obras prioritarias en inversión pública.

- **Dashboard en Tableau**: Se creó una visualización avanzada que facilita una exploración visual de los datos y permite filtrar y segmentar las obras según diferentes variables de interés:
  - **Mapa interactivo**: que muestra la distribución geográfica de las obras a nivel provincial.
  - **Análisis temporal**: que permite visualizar el progreso de las obras en distintos años.
  - **Desglose por tipo y estado de obra**: facilitando el análisis de las categorías de obra más relevantes y su estado actual.

### Resultados Clave
Este análisis permitió obtener una visión general del estado de las obras públicas en Argentina, destacando las regiones con mayor y menor inversión, así como los tipos de proyectos más comunes y su nivel de avance. Estos insights son valiosos para comprender las tendencias de inversión y posibles áreas de mejora en la gestión de obras públicas.

---

## Proyecto 4: [Fiestas Populares en Argentina](https://github.com/AlvarezLI/PowerBi-CostumbresArg/tree/main)

Este proyecto se centra en el análisis de eventos y festividades populares en Argentina a través de un informe desarrollado en **Power BI**. Se busca explorar la asistencia a eventos, la ubicación de los mismos, y la temática de cada evento.

### Fuente del conjunto de datos
El conjunto de datos utilizado en este proyecto es una recopilación de información sobre eventos y festividades populares en Argentina, que incluye detalles como la cantidad de asistentes, la ubicación de los eventos, y la temática de cada evento.

### Técnicas de análisis y preprocesamiento de datos
Para preparar y analizar los datos, se utilizaron las siguientes técnicas:

- **Control de valores nulos**: Se manejaron adecuadamente los valores faltantes para asegurar la integridad del conjunto de datos.
- **Codificación de variables categóricas**: Se transformaron las características categóricas en valores numéricos, lo cual es fundamental para el análisis de datos.
  
### Visualización y análisis
Se desarrolló un dashboard en Power BI que permite explorar diferentes aspectos de los eventos:

- **Asistentes**: Incluye gráficos que muestran la cantidad de asistentes por mes, año y tipo de entrada, junto con KPIs que resaltan la asistencia total y promedio a eventos.
- **Información**: Presenta un mapa que muestra la distribución de eventos por provincia, un KPI de eventos únicos y un gráfico de asistentes promedio por provincia.
- **Temática**: Permite explorar la temática de los eventos, mostrando la clasificación por tipo de entrada y la cantidad de eventos según su temática principal, además de KPIs relevantes como el evento más popular.

### Resultados Clave
Este análisis proporciona una visión integral de la participación en festividades populares en Argentina, destacando tendencias en la asistencia, distribución geográfica de los eventos, y temáticas predominantes. Los insights obtenidos son útiles para la planificación de futuras festividades y la evaluación de la participación del público.

---

## Proyecto 5: [Análisis de música en Spotify](https://github.com/AlvarezLI/PowerBI_Spotify)

Este proyecto se centra en el análisis de datos de canciones en Spotify, con el objetivo de explorar las características musicales y la popularidad de diferentes pistas.

### Fuente del conjunto de datos
El conjunto de datos utilizado en este proyecto proviene de la **API de Spotify**, que proporciona información detallada sobre diversas canciones, incluyendo atributos como el tempo, la energía, la danza y la popularidad.

### Técnicas de preprocesamiento de datos
Se implementaron varias técnicas de preprocesamiento para preparar los datos para el análisis:

- **Manejo de valores nulos**: Se identificaron y gestionaron los valores faltantes para mantener la calidad del conjunto de datos.
- **Normalización de datos**: Se aplicó la normalización a las características numéricas para asegurar que todos los atributos contribuyan equitativamente al análisis.
- **Codificación de variables categóricas**: Las características categóricas se transformaron en un formato adecuado para el análisis y la visualización.

### Análisis y visualización
Se realizaron diversos análisis y visualizaciones para obtener insights sobre las canciones:

- **Distribución de características musicales**: Se exploraron gráficos que muestran la distribución de atributos como el tempo, la energía y la danza de las canciones.
- **Relación entre popularidad y características**: Se analizaron gráficos de dispersión para observar cómo las diferentes características musicales afectan la popularidad de las canciones.
- **Tendencias a lo largo del tiempo**: Se examinaron las tendencias en la popularidad de las canciones a lo largo del tiempo y cómo las características musicales han cambiado.

### Resultados Clave
Este análisis permitió identificar las características musicales que más influyen en la popularidad de las canciones en Spotify, así como las tendencias en el tiempo. Los insights obtenidos son valiosos para comprender cómo las preferencias de los oyentes cambian y qué atributos musicales son más atractivos.

---
