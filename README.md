# Portafolio Alvarez Luis Ignacio

## Proyecto 1: [Modelo de comestibilidad de los hongos]](https://github.com/AlvarezLI/ProjectDS-Mushrooms)  
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
