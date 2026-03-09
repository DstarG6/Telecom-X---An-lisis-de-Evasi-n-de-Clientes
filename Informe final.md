# Análisis de Evasión de Clientes (Churn) – Telecom X

## Introducción

La evasión de clientes (Churn) ocurre cuando un cliente decide cancelar un servicio. Para las empresas de telecomunicaciones esto representa una pérdida importante, ya que adquirir nuevos clientes suele ser más costoso que mantener los actuales.

El objetivo de este proyecto es analizar los datos de clientes de Telecom X para identificar patrones relacionados con la cancelación del servicio. A través del análisis exploratorio de datos se busca entender qué factores pueden influir en la decisión de los clientes de permanecer o abandonar la empresa.

---

## Limpieza y Tratamiento de Datos

Antes de realizar el análisis fue necesario preparar y limpiar el dataset.

Se realizaron los siguientes pasos:

- Importación del dataset.
- Normalización de datos en formato JSON a columnas estructuradas.
- Conversión de nombres de columnas a minúsculas.
- Transformación de valores categóricos (Yes / No) a valores binarios (1 / 0).
- Conversión de variables numéricas al formato adecuado.
- Eliminación de valores nulos y registros duplicados.

Este proceso permitió trabajar con un conjunto de datos limpio y preparado para el análisis.

---

## Análisis Exploratorio de Datos

Durante el análisis exploratorio se examinaron diferentes variables para identificar patrones relacionados con la evasión de clientes.

### Distribución de clientes

Primero se analizó la cantidad de clientes que permanecen activos frente a los que cancelaron el servicio.

El análisis muestra que la mayoría de los clientes continúa utilizando el servicio, aunque existe un porcentaje importante que ha cancelado.

### Variables categóricas

Se analizaron diferentes variables categóricas que pueden influir en la evasión de clientes:

- Tipo de contrato
- Método de pago
- Tipo de servicio de internet
- Servicios adicionales

Los resultados muestran que los contratos de mayor duración presentan menores tasas de cancelación.

### Variables numéricas

También se analizaron variables numéricas importantes:

- Tenure (tiempo de permanencia del cliente)
- Monthly Charges (cargos mensuales)
- Total Charges (cargos totales)

Los gráficos permiten observar cómo se distribuyen estas variables entre clientes activos y clientes que cancelaron el servicio.

---

## Conclusiones

A partir del análisis realizado se identificaron algunos patrones importantes:

- Los clientes con menor tiempo en la empresa tienen mayor probabilidad de cancelar el servicio.
- Los contratos a largo plazo presentan menor nivel de evasión.
- Algunos planes con cargos mensuales más altos parecen estar asociados con mayor cancelación.
- El tipo de servicio contratado también puede influir en la permanencia del cliente.

Estos hallazgos ayudan a comprender mejor el comportamiento de los clientes.

---

## Recomendaciones

Con base en los resultados obtenidos se proponen algunas estrategias para reducir la evasión de clientes:

- Ofrecer incentivos para contratos de mayor duración.
- Implementar estrategias de retención para clientes nuevos.
- Revisar los planes con cargos mensuales más altos.
- Realizar seguimiento a clientes con mayor riesgo de cancelación.

Estas acciones pueden ayudar a mejorar la satisfacción del cliente y aumentar la retención.

---

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## Autor
- Starlyn Manuel Duarte Guzman

Proyecto de análisis de datos enfocado en el estudio de la evasión de clientes en Telecom X.
