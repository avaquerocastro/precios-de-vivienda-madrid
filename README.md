# 🚧 - - - **PROYECTO EN CONSTRUCCIÓN** - - - 🚧

# 🏢 🏠 **Predicción de precios de la vivienda en Madrid**  

Este proyecto se desarrolla como parte del **Trabajo Final de Máster** del programa **Máster en Data Science & AI** de **Nuclio Digital School**. Los integrantes del grupo de trabajo son: **Silvia González, Gilberto Sosa y Alejandra Vaquero**.  

---

## 💼 **Introducción**  

La problemática de la vivienda en España, y en particular en Madrid, es un tema de gran relevancia socioeconómica y de intenso debate en la actualidad. El acceso a la vivienda, la volatilidad del mercado inmobiliario y la influencia de factores macroeconómicos han generado la necesidad de herramientas analíticas que permitan comprender y predecir la evolución de los precios en este sector.  

En este contexto, el presente estudio tiene como objetivo desarrollar modelos predictivos de precios de vivienda en Madrid capital, aprovechando técnicas avanzadas de análisis de datos y aprendizaje automático (*Machine Learning*). Para ello, se cuenta con un **conjunto de datos de 10,528 viviendas**, cada una caracterizada por **60 variables**, que incluyen atributos estructurales, ubicación, superficies, número de habitaciones, precios históricos, entre otros factores clave.  

Este proyecto no solo busca desarrollar un modelo de predicción de precios de viviendas con alta precisión, sino también extraer conocimiento valioso sobre los factores que determinan la evolución del mercado inmobiliario en Madrid. El uso de técnicas de ciencia de datos permitirá obtener una visión más clara y estructurada del sector, facilitando la toma de decisiones tanto para inversores, compradores como para instituciones reguladoras.

---  

## 📊 **Objetivos**  

1. **Análisis Exploratorio de Datos (EDA)**  
   - Identificar patrones y tendencias en el mercado inmobiliario madrileño.  
   - Detectar valores atípicos y estrategias para su tratamiento.  
   - Imputar valores faltantes utilizando técnicas estadísticas y de aprendizaje automático.  
   - Analizar la distribución de las variables y su relación con el precio de venta.  
   - Identificar correlaciones entre variables clave para comprender su impacto en la fijación de precios.  

2. **Desarrollo y optimización de Modelos Predictivos**  
   - Implementar modelos de regresión avanzados para la predicción de precios, incluyendo enfoques basados en regresión lineal, árboles de decisión y métodos más sofisticados como *Gradient Boosting Machines* (GBM), *Random Forest* y redes neuronales. 
   - Comparar el rendimiento de diferentes algoritmos mediante métricas como *RMSE* (Root Mean Squared Error), *MAE* (Mean Absolute Error) y *R²* (coeficiente de determinación).  
   - Ajustar hiperparámetros para mejorar la precisión de las predicciones mediante técnicas como búsqueda en malla (*Grid Search*) y búsqueda aleatoria (*Random Search*).  
   - Aplicar validación cruzada (*cross-validation*) para evaluar la generalización de los modelos y evitar el sobreajuste (*overfitting*).  

3. **Interpretabilidad del Modelo y Análisis de Variables**  
   - Evaluar la importancia de las distintas variables en la predicción de precios mediante técnicas como *SHAP values* y *Feature Importance*.  
   - Identificar qué factores influyen más en la variación de precios y cómo afectan la predicción final.  
   - Proporcionar insights sobre la relación entre características como ubicación, superficie, antigüedad del inmueble y la valoración final del mercado.  

4. **Visualización y Comunicación de Resultados**  
   - Desarrollar dashboards y visualizaciones gráficas que faciliten la interpretación de los resultados.  
   - Presentar hallazgos clave mediante gráficos de dispersión, mapas de calor y representaciones geoespaciales para evidenciar tendencias en diferentes zonas de Madrid.  

5. **Aplicación de Conocimientos Adquiridos en el Máster**  
   - Implementar las técnicas y metodologías aprendidas a lo largo del Máster en *Data Science & AI*, integrando análisis estadístico, programación en Python, modelado predictivo y optimización de modelos.  
   - Fomentar una aproximación práctica y aplicada al problema, utilizando herramientas y librerías de ciencia de datos como *pandas, scikit-learn, XGBoost, TensorFlow* y *Matplotlib/Seaborn* para visualización de datos.  

---

## 📂 **Estructura del repositorio**

### 📈 `código`: esta carpeta contiene todos los `Notebooks` y los archivos `.csv` y `.xlsx` de datos utilizados y generados en el proyecto.
- `preprocesamiento-de-datos`: incluye las versiones originales y procesadas de los datos antes del modelado. Aquí se realizan acciones de limpieza, transformación y preparación de los datos.
  - `datos-pisos`: contiene los datos brutos sobre viviendas en Madrid, junto con los Notebooks utilizados para su extracción, limpieza y normalización.
  - `datos-adicionales`: incluye información complementaria, como datos geográficos, indicadores económicos y otras variables externas relevantes.
- `02-EDA-y-feature-engineering`: contiene análisis exploratorio de datos (EDA) y la selección/creación de características relevantes para el modelado.
- `clustering`: incluye experimentos y resultados de técnicas de agrupamiento para segmentación de datos.
- `modelado`: almacena los Notebooks y datasets utilizados en la construcción, entrenamiento y ajuste de modelos de predicción.
- `prediccion`: contiene los modelos finales evaluados, los resultados obtenidos y los datos utilizados para generar predicciones.

### 📄 `docs`: contiene la documentación del proyecto y otros recursos auxiliares.
- `el-proyecto`: documentos explicativos sobre el objetivo del proyecto, metodología utilizada y hallazgos clave.
- `imagenes`: gráficos, diagramas y otras representaciones visuales del análisis.
