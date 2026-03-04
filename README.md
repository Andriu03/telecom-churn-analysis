#  Telecom X - Análisis de Evasión de Clientes (Churn)

##  Descripción

Este proyecto analiza los factores que influyen en la evasión de clientes (Churn) en Telecom X.

A través de un proceso de ETL (Extracción, Transformación y Carga) y Análisis Exploratorio de Datos (EDA), se identificaron patrones relevantes que pueden contribuir a la toma de decisiones estratégicas para reducir la tasa de cancelaciones.

---

##  Objetivo del Proyecto

- Comprender el comportamiento de los clientes.
- Identificar variables asociadas a la evasión.
- Generar insights accionables para el equipo de Data Science.

---

##  Tecnologías Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Proceso de Análisis

###  Extracción
- Importación de datos desde una API en formato JSON.

###  Transformación
- Normalización de estructuras anidadas.
- Conversión a formato tabular.
- Verificación de tipos de datos.
- Revisión de valores nulos y duplicados.
- Creación de variable adicional (`Cuentas_Diarias`).

###  Análisis Exploratorio (EDA)
- Estadísticas descriptivas.
- Distribución de la variable Churn.
- Análisis de evasión según tipo de contrato.
- Comparación de cargos mensuales según evasión.
- Evaluación del tiempo de permanencia (tenure).

---

##  Principales Hallazgos

- Los contratos **mensuales** presentan mayor tasa de evasión.
- Clientes con **cargos mensuales más elevados** tienden a cancelar con mayor frecuencia.
- Un menor **tiempo de permanencia** está asociado a mayor churn.

---

##  Recomendaciones Estratégicas

- Incentivar contratos de largo plazo.
- Implementar estrategias de fidelización durante los primeros meses.
- Analizar beneficios personalizados para clientes con altos cargos mensuales.

---

##  Aprendizajes

Durante este proyecto se fortalecieron habilidades en:

- Manipulación y limpieza de datos con Pandas.
- Normalización de archivos JSON anidados.
- Análisis exploratorio de datos.
- Interpretación de métricas de negocio.
- Comunicación de resultados técnicos de forma clara.

---

##  Próximos Pasos

- Implementar modelos predictivos de churn.
- Crear dashboard interactivo.
- Analizar correlaciones entre variables numéricas.

---

## Estructura del Repositorio

- `telecom.ipynb` → Notebook con el análisis completo.
- `README.md` → Documentación del proyecto.
