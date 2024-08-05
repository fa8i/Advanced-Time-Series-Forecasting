# Time Series Forecasting with Past Regressor Variables

This project is a knowledge test on time series applied to pollution analysis. The objective is to use machine learning techniques, specifically recurrent neural networks. For this particular case, the use of an MLP has been adapted instead of a common LSTM, to predict and analyze pollution data over time. This methodology is applicable to financial sectors, climatology, price prediction...

This exercise has been carried out with a series of restrictions on the dataset:

1. The dataset must not be financial
2. The dataset is multivariate
3. The dependent variable will not have seasonality, but the regressors may have it
4. The prediction will be made without providing exogenous regressors at any point in the "future"
5. 100 future time instances will be predicted.

## Notebook Contents

The notebook contains the following sections:

1. **Data Loading**: In this section, time series data related to pollution is loaded and explored.
2. **Data Preprocessing**: Necessary transformations are performed to prepare the data for the MLP model.
3. **Model Definition**: The architecture of the MLP model used for prediction is defined.
4. **Model Training**: The model is trained with the preprocessed data.
5. **Model Evaluation**: The model's performance is evaluated using appropriate metrics.
6. **Results Visualization**: Predictions are visualized and compared with real data.

## Requirements

To run the notebook, you will need to have the following libraries installed:

- numpy
- pandas
- scikit-learn
- matplotlib
- tensorflow or keras

You can install them using pip:

```bash
pip install numpy pandas scikit-learn matplotlib tensorflow
```

## Usage

To use this notebook:

1. Clone this repository:
    ```bash
    git clone https://github.com/fa8i/Advanced-Time-Series-Forecasting.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Advanced-Time-Series-Forecasting
    ```
3. Open the notebook:
    ```bash
    jupyter notebook SSTT_MLP.ipynb
    ```

4. Execute the notebook cells to reproduce the analysis and predictions.

## Contributions

Contributions are welcome. Please open an issue or submit a pull request to improve this project.

## Contact

For more information or references, you can contact me at:

- fabianmp_98@hotmail.com
- github.com/fa8i

_______________________________________________________________________________________________________

# Spanish:
# SSTT Predicción de Futuro con variables regresoras pasadas

Este proyecto es una prueba de conocimiento sobre series temporales aplicada al análisis de la contaminación. El objetivo es utilizar técnicas de aprendizaje automático, específicamente redes neuronales recurrenntrs. Para este caso en concreto se ha adaptado el uso de una MLP en lugar de usar un LSTM común, para predecir y analizar datos de contaminación a lo largo del tiempo. Esta metodología es aplicable a sectores tanto financieros, climatológigos, predicción de precios...

Este ejercicio se ha realizado con una serie de restricciones sobre el dataset:

1. El conjunto de datos no debe ser financiero
2. El conjunto de datos es **multivariante**
3. La variable dependiente **no tendra estacionalidad**, pero los regresores sí pueden tenerla.
4. La predicción se realizará **sin proporcionar regresores exógenos** en ningún punto del "futuro"
5. Se predecirán 100 instantes de tiempo futuro.

## Contenido del Notebook

El notebook contiene las siguientes secciones:

1. **Carga de datos**: En esta sección, se cargan y exploran los datos de series temporales relacionados con la contaminación.
2. **Preprocesamiento de datos**: Se realizan las transformaciones necesarias para preparar los datos para el modelo de MLP.
3. **Definición del modelo**: Se define la arquitectura del modelo de MLP utilizado para la predicción.
4. **Entrenamiento del modelo**: Se entrena el modelo con los datos preprocesados.
5. **Evaluación del modelo**: Se evalúa el rendimiento del modelo utilizando métricas adecuadas.
6. **Visualización de resultados**: Se visualizan las predicciones y se comparan con los datos reales.

## Requisitos

Para ejecutar el notebook, necesitarás tener instaladas las siguientes librerías:

- numpy
- pandas
- scikit-learn
- matplotlib
- tensorflow o keras

Puedes instalarlas usando pip:

```bash
pip install numpy pandas scikit-learn matplotlib tensorflow
```

## Uso

Para utilizar este notebook:

1. Clona este repositorio:
    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd Advanced-Time-Series-Forecasting
    ```
3. Abre el notebook:
    ```bash
    jupyter notebook SSTT_MLP.ipynb
    ```

4. Ejecuta las celdas del notebook para reproducir el análisis y las predicciones.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para mejorar este proyecto.

## Contacto

Para más información o referencias, mi contacto es:

- fabianmp_98@hotmail.com
- github.com/fa8i
