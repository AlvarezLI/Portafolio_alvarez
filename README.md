# Portafolio Alvarez Luis Ignacio

¡Bienvenido a mi portafolio de ciencia de datos! En esta colección, encontrarás varios proyectos que demuestran mis habilidades en análisis de datos, aprendizaje automático y visualización de datos. El portafolio incluye proyectos tanto en **inglés** como en **español**.

---

## Data Science Projects (English - Python)

### Project 1: Mushroom Edibility Model
This project is part of my final exam for a data science course, where I classified different mushrooms based on their edibility.

**Dataset Source**  
The dataset used in this project is the **Mushroom Classification dataset** from Kaggle, which provides a comprehensive description of mushroom characteristics.

**Data Preprocessing Techniques**  
Various filtering techniques were employed to prepare the data, including:

- **Null Value Checks:** Ensured the dataset's integrity by appropriately handling missing values.
- **Categorical Variable Encoding:** Transformed categorical features into numerical values for effective machine learning training.

**Machine Learning Algorithms**  
The following algorithms were applied for data analysis and classification:

- Random Forest Classifier
- Support Vector Machine (SVM)
- Logistic Regression

---

### Project 2: Weather Prediction Model
In this project, I conducted an in-depth analysis of a synthetic dataset designed to classify different weather types.

**Dataset Source**  
The dataset used in this project is the **Weather Type Classification** from Kaggle, which is synthetically generated to mimic weather data for classification tasks. 

**Data Preprocessing Techniques**  
The following techniques were implemented to prepare the data:

- **Handling and Imputation of Missing Values:** Addressed missing values to maintain the dataset's quality.
- **Categorical Variable Encoding:** Converted categorical variables into a suitable format for model training.
- **Outlier Removal:** Applied the interquartile range (IQR) method to eliminate outliers.

**Machine Learning Algorithms**  
Several classification algorithms were implemented to predict weather types, including:

- Random Forest Classifier
- Gradient Boosting Machine (GBM)
- Logistic Regression
- Decision Tree Classifier

**Model Optimization and Evaluation**  
Each model was evaluated using key metrics such as:

- **Accuracy:** Measurement of the overall correctness of predictions.
- **Confusion Matrix:** Assessment of classification model performance.

The models were compared to identify the best fit for predicting weather types, and hyperparameter optimization was performed to improve the results.

---

### Project 3: Animal Classification with CNN and Transfer Learning
In this project, I developed and compared two distinct models for classifying images of animals (dogs, cats, and snakes): a simple Convolutional Neural Network (CNN) and an improved model leveraging transfer learning with MobileNetV2.

**Dataset Source**  
The dataset used in this project is the **Animal Image Classification Dataset** from Kaggle, which is a comprehensive collection of images tailored for the development and evaluation of machine learning models in the field of computer vision. It contains 3,000 JPG images, carefully segmented into three classes representing common pets and wildlife: cats, dogs, and snakes.

**Data Preprocessing Techniques**  
The following steps were applied:

- **Image Augmentation:** Techniques like rotation, flipping, and zooming were used to enhance model generalization.
- **Train-Test Split:** The dataset was divided into 80% for training and 20% for testing.

**Model Development**

1. **Simple CNN Model:**  
   - Architecture: Included convolutional layers, max-pooling, and dense layers.  
   - Performance:  
     - Training accuracy: ~89%  
     - Validation accuracy: ~45%  
     - Challenges: High validation loss and signs of overfitting.  

2. **Improved Model with MobileNetV2:**  
   - Transfer Learning: Used MobileNetV2 pre-trained on ImageNet.  
   - Performance:  
     - Training accuracy: 96.1% (15th epoch)  
     - Validation accuracy: 96%  
     - Final validation loss: 0.09  

**Key Takeaways**  
- Transfer learning significantly improved validation accuracy and reduced overfitting.
- Leveraging pre-trained features allowed the improved model to generalize better on unseen data.

---

## Proyectos de Data Analytics (Español - Excel, Tableau, PowerBI)

### Proyecto 4: Análisis de Obras Públicas en Excel y Tableau
Este proyecto se enfoca en realizar un análisis extenso de los datos de obras públicas en Argentina. El objetivo fue obtener información sobre la distribución y el estado de las inversiones en infraestructura a nivel regional, utilizando Excel y Tableau para una mejor visualización y análisis de los datos.

**Fuente del Dataset**  
El dataset fue obtenido del Mapa de Inversiones del Ministerio de Obras Públicas de Argentina, que proporciona información detallada sobre las obras públicas en diversas provincias y su estado de avance.

**Técnicas de Análisis y Preprocesamiento de Datos**  
- Limpieza y Validación de Datos  
- Tablas Dinámicas  
- Segmentación de Datos  

**Visualización y Dashboard**  
- Dashboard interactivo en Excel y Tableau para explorar la distribución de las obras.

**Resultados Clave**  
Este análisis proporcionó una visión general sobre el estado de las obras públicas en Argentina.

---

### Proyecto 5: Análisis de Festivales Populares en Argentina
Este proyecto está enfocado en analizar eventos y festivales populares en Argentina a través de un informe en Power BI. El objetivo fue explorar la asistencia a los eventos, sus ubicaciones y los temas de cada evento.

**Fuente del Dataset**  
El dataset utilizado en este proyecto es una compilación de información sobre eventos y festivales populares en Argentina.

**Técnicas de Preprocesamiento de Datos**  
- Control de Valores Nulos  
- Codificación de Variables Categóricas  

**Visualización y Análisis**  
- Dashboard interactivo en Power BI para explorar diferentes aspectos de los eventos.

**Resultados Clave**  
Este análisis ofrece una visión integral de la participación en festivales populares en Argentina.

---

### Proyecto 6: Análisis de Datos Musicales de Spotify
Este proyecto se enfoca en analizar los datos de canciones de Spotify, con el objetivo de explorar las características musicales y su relación con la popularidad de las canciones.

**Fuente del Dataset**  
El dataset utilizado en este proyecto fue descargado de Kaggle.

**Técnicas de Preprocesamiento de Datos**  
- Extracción de Datos  
- Visualización de Datos  

**Visualización y Análisis**  
- Distribución del Tempo  
- Energía vs Popularidad  

**Resultados Clave**  
Este análisis proporciona información sobre cómo las características musicales influyen en la popularidad de las canciones en Spotify.

---

Siéntete libre de explorar cada proyecto para obtener detalles más profundos sobre mi recorrido en ciencia de datos. Para más información sobre cada uno de los proyectos, sigue los enlaces proporcionados a los repositorios de GitHub.
