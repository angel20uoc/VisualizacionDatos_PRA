# Proyecto de Visualización de Datos: Análisis del Sistema Eléctrico Español (2015–2018)

Este repositorio contiene el material completo del proyecto final de la asignatura **Visualización de Datos**, realizado en el marco del **Máster Universitario en Ciencia de Datos de la UOC**.

## 🔗 Visualización interactiva

Puedes explorar la visualización final publicada en Flourish en el siguiente enlace:

👉 [Visualización interactiva en Flourish](https://public.flourish.studio/story/3157753/)

Esta visualización interactiva permite explorar la evolución de los precios eléctricos reales y previstos, la relación con el uso de energías renovables y los patrones diarios del sistema eléctrico español.

---

## 📂 Estructura del repositorio

### `/R`

En esta carpeta encontrarás todo el material necesario para reproducir el procesamiento de datos y la preparación de los datasets:

- `energy_dataset.csv`: Dataset original, obtenido de Kaggle.
- `PRA_parte2.Rmd`: Documento en formato Markdown ejecutable en RStudio, donde se realiza el análisis, limpieza y transformación de datos.
- `*.csv`: Archivos individuales generados a partir del análisis, que sirven como fuente directa para cada una de las escenas de la visualización en Flourish.

---

## 📊 Descripción del dataset

El conjunto de datos original incluye registros horarios entre 2015 y 2018 del sistema eléctrico español. Contiene variables relacionadas con:

- Producción de energía por fuente (renovable y no renovable)
- Consumo eléctrico
- Precios del mercado: día anterior (`day ahead`) y reales (`actual`)
- Predicciones oficiales de generación y demanda

Fuente: [Kaggle - Energy Consumption, Generation, Prices and Weather](https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather)

---

## 📌 Objetivo del proyecto

El objetivo principal ha sido transformar un dataset complejo y multivariable en una **historia visual** clara, estructurada e interactiva que responda a las siguientes preguntas clave:

1. ¿Cómo evolucionan los precios reales frente a los precios previstos hora a hora?
2. ¿Qué relación existe entre el uso de fuentes renovables y los precios del mercado?
3. ¿Es posible identificar perfiles de generación/consumo asociados a distintos días de la semana?

---

