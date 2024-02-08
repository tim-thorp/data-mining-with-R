# CAST: Minería de Datos

(Please see below for English translation)

## Resumen

Este proyecto se completó como parte de la asignatura «Minería de Datos» en la Universitat Oberta de Catalunya (UOC). Utilizando R como el principal lenguaje de programación, el proyecto se divide en dos partes: «PRA1» y «PRA2». Cubre un amplio rango de técnicas de minería de datos, desde el procesamiento de datos preparatorios hasta la aplicación y evaluación de modelos de aprendizaje automático tanto supervisados como no supervisados.

La primera mitad del proyecto (PRA1) incluye lo siguiente:

- Establecimiento del objetivo analítico
- Obtención del conjunto de datos
- Limpieza de los datos
- Análisis exploratorio
- Discretización de atributos
- Transformación de atributos
- Análisis de correlación
- Descomposición en Valores Singulares (SVD)

La segunda mitad del proyecto (PRA2) incluye lo siguiente:

- Modelos no supervisados
  - *k*-means (distancia euclidiana)
  - *k*-medians (distancia de Manhattan)
  - OPTICS y DBSCAN
- Modelos supervisados
  - Algoritmos de árboles de decisión: C5.0 y CART
  - Método de ensamble: Bosque Aleatorio
- Evaluación y comparación del rendimiento de los modelos
  - Matriz de confusión
  - Curva PR

## Estructura del Repositorio

- **`/src`**: Contiene el código fuente en R markdown (.rmd) para tanto PRA1 como PRA2.
- **`/data`**: 
  - `flightData.csv`: El conjunto de datos original.
  - `flightData_clean.csv`: El conjunto de datos procesado después de PRA1.
- **`/docs`**: Los informes del proyecto en formatos PDF y HTML.


## Instrucciones de Ejecución

Para ejecutar el proyecto, descarga los archivos R markdown (.rmd) y ejecútalos utilizando R Studio.

## Bibliografía

Bureau of Transportation Statistics. (2023). *TranStats.* Recuperado de https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr

GeeksforGeeks. (2023). *Dummy Variables in R Programming.* Recuperado de https://www.geeksforgeeks.org/dummy-variables-in-r-programming/

Gironés Roig, J. (2023). *Gestión de características.* Universitat Oberta de Catalunya.

Gironés Roig, J. (2023). *Modelos no supervisados.* Universitat Oberta de Catalunya.

Kaplan, J. & Schlegel, B. (2023). *fastDummies: Fast Creation of Dummy (Binary) Columns and Rows from Categorical Variables* (Versión 1.7.1). Recuperado de https://jacobkap.github.io/fastDummies/

Montoliu Colás, R. (2023). *Evaluación de modelos.* Universitat Oberta de Catalunya.

Montoliu Colás, R. (2023). *Preprocesado de datos.* Universitat Oberta de Catalunya.

Peng, R. D. (2023). *Dimension Reduction. En Exploratory Data Analysis.* Recuperado de https://bookdown.org/rdpeng/exdata/dimension-reduction.html

R Core Team. (2023). *Documentación sobre SVD.* Recuperado de https://www.rdocumentation.org/packages/base/versions/3.6.2/topics/svd



# ENG: Data Mining

## Overview

This project was completed as part of the "Data Mining" subject at the Open University of Catalonia (UOC). Utilizing R as the primary programming language, the project is divided into two parts: "PRA1" and "PRA2". It covers a comprehensive range of data mining techniques, from preparatory data processing to the application and evaluation of both supervised and unsupervised machine learning models.

The first half of the project (PRA1) includes the following:

- Establishing the analytical objective
- Obtaining the dataset
- Cleaning the data
- Exploratory analysis
- Discretization of attributes
- Transformation of attributes
- Correlation analysis
- Singular Value Decomposition (SVD)

The second half of the project (PRA2) includes the following:

- Unsupervised models
  - *k*-means (euclidian distance)
  - *k*-medians (Manhattan distance)
  - OPTICS and DBSCAN
- Supervised models
  - Decision trees algorithms: C5.0 and CART
  - Ensemble method: Random Forest
- Evaluation and comparison of model performance
  - Confusion matrix
  - PR Curve

## Repository Structure

- **`/src`**: Contains R markdown (.rmd) source code for both PRA1 and PRA2.
- **`/data`**: 
  - `flightData.csv`: Original dataset.
  - `flightData_clean.csv`: Processed dataset post-PRA1.
- **`/docs`**: Project reports in PDF and HTML formats.


## Execution Instructions

To run the project, download the R markdown files (.rmd) and execute them using R Studio.

## Bibliography

Bureau of Transportation Statistics. (2023). *TranStats.* Retrieved from [https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr](https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr)

GeeksforGeeks. (2023). *Dummy Variables in R Programming.* Retrieved from [https://www.geeksforgeeks.org/dummy-variables-in-r-programming/](https://www.geeksforgeeks.org/dummy-variables-in-r-programming/)

Gironés Roig, J. (2023). *Feature Management & Unsupervised Models.* Open University of Catalonia.

Kaplan, J. & Schlegel, B. (2023). *fastDummies: Fast Creation of Dummy Columns.* Retrieved from [https://jacobkap.github.io/fastDummies/](https://jacobkap.github.io/fastDummies/)

Montoliu Colás, R. (2023). *Model Evaluation & Data Preprocessing.* Open University of Catalonia.

Peng, R. D. (2023). *Dimension Reduction.* Retrieved from [https://bookdown.org/rdpeng/exdata/dimension-reduction.html](https://bookdown.org/rdpeng/exdata/dimension-reduction.html)

R Core Team. (2023). *SVD Documentation.* Retrieved from [https://www.rdocumentation.org/packages/base/versions/3.6.2/topics/svd](https://www.rdocumentation.org/packages/base/versions/3.6.2/topics/svd)