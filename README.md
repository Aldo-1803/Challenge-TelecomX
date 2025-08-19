# 📊 Telecom X — Análisis de Evasión de Clientes (Churn)

## 📌 Descripción
Este proyecto corresponde a un **challenge del Curso de Data Science**.  
El objetivo es analizar la **evasión de clientes (churn)** en la empresa ficticia **Telecom X**, identificando los factores más relevantes asociados a la baja y proponiendo estrategias para reducir la pérdida de clientes.

---

## 🎯 Objetivos
- Comprender los factores que influyen en la **cancelación de clientes**.  
- Practicar un flujo completo de **ETL**: extracción, transformación y carga de datos.  
- Realizar un **Análisis Exploratorio de Datos (EDA)** con Python.  
- Identificar **insights accionables** para la toma de decisiones.  
- Proponer **estrategias de retención** basadas en datos.  

---

## 🛠️ Tecnologías utilizadas
- **Python 3**  
- **Librerías principales:**  
  - `pandas` → manipulación de datos  
  - `numpy` → cálculos estadísticos  
  - `matplotlib` & `seaborn` → visualizaciones  
  - `requests` → extracción de datos desde API  

---

## 📂 Estructura del Notebook
1. **Extracción**  
   - Obtención de datos desde API / GitHub RAW.  
   - Conversión a DataFrame.  

2. **Transformación**  
   - Aplanado de columnas anidadas (`customer`, `phone`, `internet`, `account`).  
   - Normalización de nombres y estandarización de categorías (`yes/no`).  
   - Manejo de valores nulos (`churn`, `chargestotal`).  
   - Creación de la columna derivada `cuentas_diarias`.  

3. **Análisis Exploratorio (EDA)**  
   - Estadísticos descriptivos (media, mediana, desviación, cuartiles).  
   - Distribución global de churn.  
   - Comparación de churn según variables categóricas (contrato, método de pago, facturación, internet).  
   - Comparación de churn según variables numéricas (tenure, cargos mensuales, total, cuentas diarias).  
   - Visualizaciones clave.  

4. **Informe Final**  
   - Conclusiones sobre patrones detectados.  
   - Insights de negocio.  
   - Recomendaciones estratégicas.  

---

## 📊 Principales hallazgos
- La **tasa de churn** es aproximadamente **26–27%**.  
- Los clientes con **contrato mes a mes** presentan mayor probabilidad de cancelar.  
- Los clientes con **pocos meses de antigüedad (tenure bajo)** muestran más evasión.  
- **Cargos mensuales altos** están asociados a mayor churn.  
- Los que **no contratan servicios adicionales** (seguridad, soporte, etc.) tienden a irse más.  
- Métodos de pago como **electronic check** muestran mayor churn relativo.  

---

## 💡 Recomendaciones
- Incentivar contratos de **mayor plazo** (1–2 años).  
- Ofrecer **bundles de servicios adicionales** para aumentar fidelización.  
- Implementar **programas de retención temprana** en clientes nuevos (primeros 3 meses).  
- Revisar políticas de **precios y facturación electrónica**.  
- Monitorear clientes con **cargos altos** y aplicar descuentos dirigidos.  

--- 

## 🚀 Próximos pasos
- Entrenar un **modelo predictivo de churn** (Logistic Regression / Random Forest).  
- Explicar factores clave mediante **feature importance / SHAP**.  
- Diseñar **campañas de retención automatizadas** dirigidas a clientes de alto riesgo.  

---
