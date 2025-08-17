# Challenge-Telecom-X-parte-2

Análisis y Modelado Predictivo de Abandono de Clientes (Churn)
Descripción del Proyecto

Este proyecto tiene como objetivo analizar y predecir el abandono de clientes (churn) en una empresa de telecomunicaciones. Se realiza un proceso de extracción, preparación, análisis exploratorio de datos, y modelado predictivo utilizando Regresión Logística y Random Forest.
Contenido del Notebook

El notebook se estructura en las siguientes secciones:

    Extracción: Carga de los datos desde un archivo CSV.
    Preparación de los Datos: Limpieza, transformación y codificación de variables para el modelado. Esto incluye el manejo de valores nulos y la codificación one-hot de variables categóricas.
    Correlación y Selección de Variables: Análisis de la correlación entre las variables y la variable objetivo (Churn), y selección de variables relevantes. Se visualiza la correlación mediante un heatmap.
    Análisis Dirigido: Investigación de la relación entre variables específicas (como tiempo de contrato y gasto total) y el abandono de clientes mediante visualizaciones como boxplots.
    Modelado Predictivo:
        Separación de datos en conjuntos de entrenamiento y prueba.
        Balanceamiento de clases utilizando SMOTE para abordar el desbalance en la variable objetivo.
        Entrenamiento y evaluación de modelos de Random Forest y Regresión Logística.
        Análisis de Métricas de Evaluación (Accuracy, Precision, Recall, F1-Score) y Matriz de Confusión.
        Visualización de Curvas ROC.
    Interpretación y Conclusiones: Análisis de la importancia de las variables en el modelo Random Forest y conclusiones sobre el rendimiento de los modelos predictivos y los hallazgos clave del análisis.

Cómo Ejecutar el Código

    Abre el notebook en Google Colab.
    Ejecuta cada celda secuencialmente.

Conclusiones Principales del Análisis

    Los clientes con menor antigüedad (tenure) son más propensos a abandonar.
    Los cargos mensuales y totales elevados están asociados con una mayor tasa de abandono.
    Los contratos de pago mensual tienen una mayor tendencia al abandono en comparación con contratos a largo plazo.
    El método de pago de cheque electrónico se relaciona con una mayor probabilidad de abandono.
    El servicio de Internet de Fibra Óptica presenta una de las mayores probabilidades de deserción.

Modelos Predictivos

Se compararon dos modelos: Random Forest y Regresión Logística. Ambos modelos tuvieron un rendimiento similar, con la Regresión Logística mostrando una ligera ventaja en términos de exactitud y precisión para la clase de abandono en este conjunto de datos específico.
0,
,,,,,,,,,,
