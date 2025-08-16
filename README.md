# Challenge LATAM - Análisis de Evasión de Clientes en TelecomX

Este proyecto aborda el **problema de evasión de clientes (Churn)** en la empresa ficticia **TelecomX**.  
El análisis permite comprender **qué factores influyen en que los clientes abandonen la compañía** y qué estrategias pueden implementarse para reducir la evasión.

---

## Objetivo

- Identificar variables asociadas al churn.  
- Analizar patrones de gasto, contrato y servicios.  
- Generar recomendaciones estratégicas para retención de clientes.  

---

## Estado del proyecto: Finalizado

---

## Funcionalidades implementadas

- **Extracción y exploración de datos**  
  - Carga de datos desde JSON.  
  - Exploración de columnas, tipos de datos y valores únicos.  

- **Transformación y limpieza de datos**  
  - Expansión de diccionarios en columnas independientes.  
  - Reemplazo de valores vacíos y conversión de tipos numéricos.  

- **Análisis exploratorio (EDA)**  
  - Creación de subconjunto con variables críticas para churn.  
  - Cálculo de cargos diarios aproximados.  
  - Estadísticas descriptivas.  

- **Visualización de resultados**  
  - **Gráfico de pastel**: proporción de clientes con y sin churn.  
  - **Gráfico de barras**: distribución de churn según tipo de contrato.  
  - **Boxplot**: comparación de gasto total entre clientes que evaden y los que permanecen.  

- **Recomendación final basada en datos**  
  - Estrategias de fidelización enfocadas en clientes con contratos mensuales.  
  - Incentivar métodos de pago automáticos para reducir churn.  
  - Mejorar servicios de internet (seguridad, soporte técnico) como factores de retención.  

---

## Estructura del código

El código se encuentra en un archivo `.ipynb` y está organizado en secciones:

1. **Extracción** → carga y exploración inicial.  
2. **Transformación** → normalización y limpieza.  
3. **Carga y análisis** → estadísticas y gráficos.  
4. **Conclusiones y recomendaciones** → insights para el negocio.  

---

## Cómo ejecutar

1. Abrir el archivo `.ipynb` en [Google Colab](https://colab.research.google.com/) o Jupyter Notebook.  
2. Ejecutar las celdas en orden.  
3. Visualizar los gráficos generados y revisar el informe final en Markdown.  

---

## Requisitos

- Python 3.x  
- Bibliotecas:
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  

---

## Resultados clave

- El **26.5% de clientes abandonan la compañía**.  
- Los contratos mensuales presentan **alta tasa de evasión**.  
- Clientes con cargos elevados también muestran riesgo de churn.  
- Los métodos de pago tradicionales aumentan probabilidad de evasión.  

---

## Conclusión

El análisis demuestra que la evasión está asociada a **contratos flexibles, cargos mensuales y métodos de pago menos automatizados**.  
Se recomienda a TelecomX:  

- Incentivar contratos a largo plazo.  
- Implementar descuentos por débito automático.  
- Mejorar los servicios digitales de seguridad y soporte.  

