# challenger-2-alura-store-data-sciece
# TelecomX - Análisis de Evasión de Clientes (Churn)

## Descripción

Este proyecto realiza un **análisis exploratorio de datos (EDA)** sobre la evasión de clientes (Churn) en la empresa TelecomX.  
El objetivo es identificar **patrones y factores asociados a la cancelación del servicio** utilizando Python y técnicas de análisis de datos.

A través de la limpieza de datos, visualización y análisis estadístico, se buscan insights que ayuden a **comprender el comportamiento de los clientes y apoyar estrategias de retención**.

---

# Estructura del Proyecto:
TelecomX_LATAM.ipynb # Notebook con todo el análisis
TelecomX_Data.json # Dataset utilizado
TelecomX_diccionario.md # Diccionario de datos
README.md # Documentación del proyecto


---

# Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

# Análisis Realizado

El proyecto incluye:

### Limpieza y transformación de datos
- Conversión de variables categóricas a valores numéricos
- Corrección de tipos de datos
- Manejo de valores faltantes
- Creación de nuevas variables como **Cuentas_Diarias** y **TotalServicios**

### Análisis exploratorio
Se realizaron visualizaciones para identificar patrones de churn:

- Distribución de clientes que permanecen vs abandonan
- Churn según tipo de contrato
- Relación entre tiempo de permanencia y evasión
- Relación entre facturación y churn
- Análisis de correlación entre variables
- Número de servicios contratados vs churn

---

# Principales Insights

El análisis muestra que:

- Los clientes con contratos **Month-to-month** tienen mayor probabilidad de cancelar.
- Los clientes con **menor tiempo en la empresa** presentan mayor tasa de evasión.
- Los clientes con **facturación mensual más alta** tienden a cancelar con mayor frecuencia.
- Los clientes con **menos servicios contratados** presentan mayor riesgo de churn.

---

# Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/JuanCanchi19/challenger-2-alura-store-data-sciece.git
```

2. Abrir el notebook en:

Google Colab

Jupyter Notebook

3. Ejecutar las celdas en orden para reproducir el análisis.
   
## Posibles Mejoras

Implementar modelos de Machine Learning para predicción de churn

Crear dashboards interactivos con Power BI o Plotly

Analizar variables adicionales para mejorar la predicción

## Autor

Juan Canchila

Proyecto realizado como parte del Challenge de Data Science - Alura LATAM.
