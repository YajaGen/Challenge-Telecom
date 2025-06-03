# 📊 Análisis de Evasión de Clientes - Telecom X

Este proyecto forma parte del desafío propuesto por Alura Latam y busca analizar el comportamiento de los clientes de una empresa de telecomunicaciones, con el fin de identificar los factores que contribuyen a la evasión (churn) y proponer estrategias para su reducción.

## 🚀 Objetivo

El objetivo principal es aplicar técnicas de análisis de datos para comprender el perfil de los clientes que cancelan el servicio, generar insights accionables y fomentar la toma de decisiones basadas en datos.

## 🧰 Tecnologías utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🧹 Limpieza y Tratamiento de Datos

Se realizaron los siguientes pasos:

- Importación de datos desde una API.
- Revisión y tratamiento de valores nulos.
- Estandarización de tipos de datos.
- Creación de nuevas columnas (como facturación diaria).
- Transformación de variables categóricas a valores binarios.

## 📈 Análisis Exploratorio de Datos (EDA)

El análisis incluyó:

- Análisis descriptivo de las variables.
- Visualización de la distribución de clientes que cancelaron vs. los que no.
- Exploración de la evasión según variables categóricas (género, contrato, método de pago, etc.).
- Comparación de variables numéricas (total gastado, tiempo de contrato) por tipo de cliente (churn vs no churn).

## 📌 Principales Insights

- Los contratos mensuales tienen una tasa de evasión significativamente mayor.
- Clientes con menor tiempo de permanencia y menor facturación total tienden a cancelar el servicio con mayor frecuencia.
- Métodos de pago como "cheque electrónico" se asocian con mayor evasión.

## 🧠 Recomendaciones

- Fomentar contratos anuales o bianuales mediante descuentos o beneficios.
- Detectar clientes con baja permanencia y consumo para ofrecer retención anticipada.
- Incentivar métodos de pago automáticos para reducir cancelaciones.

## 📁 Estructura del Proyecto

