![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
![Numpy](https://img.shields.io/badge/-Numpy-333333?style=flat&logo=numpy)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-333333?style=flat&logo=matplotlib)
![Seaborn](https://img.shields.io/badge/-Seaborn-333333?style=flat&logo=seaborn)
![Scikitlearn](https://img.shields.io/badge/-Scikitlearn-333333?style=flat&logo=scikitlearn)

# Es: Proyecto de Análisis de Datos de Mercado de Automóviles 🏎️

## Descripción

Este proyecto es planteado por el Bootcamp de Data Science de "Soy Henry" y se enfoca en el análisis de datos de un conjunto de datos que contiene información sobre diferentes modelos de automóviles, incluyendo detalles sobre características técnicas, precios y más. Simularemos una situación donde Hemos sido contratados en el equipo de ciencias de datos en una consultora de renombre. Nos han asignado a un proyecto de estudio de mercado de una importante automotriz china. El objetivo principal  es analizar las características de los vehículos presentes en el conjunto de datos proporcinonado para  saber qué características presentan los vehículos de gama alta y los de gama baja en el mercado, para poder abarcar todo los públicos objetivos ajustándose a toda la demanda y, con base a estos datos, poder cotizar correctamente los vehículos que ofrecerá, para ello se desarrollarán modelos predictivos para estimar los precios de los vehículos y clasificarlos si son caros o baratos

## Notebooks

1. **cars_ETL.ipynb:** Proceso de exploración y limpieza de datos.
2. **cars_EDA.ipynb:** Ingeniería de funciones para preparar datos para el modelado.
3. **cars_modeling.ipynb:** Implementación y evaluación de modelos predictivos.

## Resumen

### Exploración y preprocesamiento de datos
Comenzamos cargando y explorando el conjunto de datos, seguido de meticulosas modificaciones y procedimientos de limpieza, adhiriéndose a criterios predefinidos destinados a abordar el problema en cuestión.

### Análisis de datos exploratorios (EDA)
A continuación se realiza un análisis de datos exploratorios (EDA) en profundidad, que aprovecha las herramientas estadísticas para descubrir características óptimas para su uso en nuestros modelos. Los datos se preparan meticulosamente para facilitar el despliegue de modelos predictivos y de clasificación.

### Entrenamiento modelo
Los modelos seleccionados reciben entrenamiento para realizar tareas específicas:

1. Predicción:
- Regresión lineal

2. Clasificación:

- Bosque aleatorio
- k-vecinos más cercanos
- Regresión logística
- Árbol de decisión

### Evaluación y selección de modelos
Después del entrenamiento, los modelos se ajustan mediante calibración de hiperparámetros. Se realiza una comparación exhaustiva para tomar decisiones informadas, asegurando la selección del modelo más eficaz para el problema determinado.

## Instalación

Bibliotecas requeridas: pandas, numpy, scikit-learn, seaborn, matplotlib, entre otras. Puedes instalarlas ejecutando

```bash
pip install -r requirements.txt
jupyter notebook
```

## Contacto

Para cualquier consulta o información adicional, no dudes en ponerte en contacto a través de este repositorio de GitHub.

## Créditos

Agradecemos a todo el equipo de "Soy Henry" y a los autores de los conjuntos de datos utilizados en este proyecto.

