📊 Análisis de Evasión de Clientes (Churn) – Telecom X
Introducción

La evasión de clientes, conocida como Churn, es uno de los principales problemas que enfrentan las empresas de telecomunicaciones. Ocurre cuando un cliente decide cancelar el servicio contratado, lo que genera pérdidas económicas y afecta la estabilidad del negocio.

El objetivo de este proyecto es analizar los datos de clientes de Telecom X para identificar patrones asociados con la cancelación del servicio. A través del análisis exploratorio de datos y visualizaciones, se busca comprender qué factores pueden influir en la evasión de clientes.

Limpieza y Tratamiento de Datos

Para comenzar el análisis fue necesario preparar y limpiar los datos. El dataset original contenía información en formato JSON, por lo que se realizó un proceso de normalización para convertirlo en columnas estructuradas.

Los principales pasos realizados fueron:

Importación del dataset.

Normalización de los datos en formato JSON.

Conversión de nombres de columnas a minúsculas.

Transformación de variables categóricas (Yes/No) a valores binarios (1/0).

Conversión de columnas numéricas al formato adecuado.

Eliminación de valores nulos y registros duplicados.

Este proceso permitió obtener un conjunto de datos limpio y adecuado para el análisis.

Análisis Exploratorio de Datos

El análisis exploratorio permitió identificar patrones relacionados con la evasión de clientes a través de diferentes variables.

Distribución de clientes

Primero se analizó la proporción de clientes que cancelaron el servicio frente a los que continúan activos.

El análisis mostró que la mayoría de los clientes permanecen activos, aunque existe un porcentaje importante que ha cancelado el servicio.

Variables categóricas

Se analizaron diferentes variables categóricas que podrían influir en la evasión de clientes, como:

Tipo de contrato

Método de pago

Tipo de servicio de internet

Servicios adicionales

Los gráficos muestran que algunos tipos de contrato presentan menores niveles de evasión, especialmente aquellos de mayor duración.

Variables numéricas

También se analizaron variables numéricas importantes como:

Tiempo de permanencia del cliente en la empresa (tenure)

Cargos mensuales (monthly charges)

Cargos totales (total charges)

Las visualizaciones permitieron observar cómo se distribuyen estas variables entre clientes activos y clientes que cancelaron el servicio.

Conclusiones e Insights

A partir del análisis realizado se identificaron varios patrones relevantes:

Los clientes con menor tiempo en la empresa tienen mayor probabilidad de cancelar el servicio.

Los contratos a largo plazo presentan menor tasa de evasión.

Algunos planes con cargos mensuales más altos parecen estar asociados con una mayor probabilidad de cancelación.

Factores como el tipo de servicio contratado y el método de pago también pueden influir en la permanencia del cliente.

Estos resultados permiten comprender mejor el comportamiento de los clientes y los factores que afectan su decisión de permanecer en la empresa.

Recomendaciones

Con base en los hallazgos del análisis, se proponen algunas recomendaciones para reducir la evasión de clientes:

Promover contratos de mayor duración mediante incentivos o beneficios.

Implementar estrategias de retención para clientes nuevos, especialmente durante los primeros meses.

Evaluar los planes con cargos mensuales elevados para mejorar su competitividad.

Realizar seguimiento a clientes con mayor riesgo de cancelación para mejorar su experiencia.

Aplicar este tipo de estrategias puede ayudar a mejorar la retención de clientes y fortalecer la relación entre la empresa y sus usuarios.

Herramientas utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab / Jupyter Notebook

Autor

Proyecto realizado como parte de un desafío de análisis de datos enfocado en el estudio de la evasión de clientes en empresas de telecomunicaciones.
