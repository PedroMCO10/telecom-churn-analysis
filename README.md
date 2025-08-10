# telecom-churn-analysis
 Análisis exploratorio de evasión de clientes para Telecom X
# Análisis de Evasión de Clientes (Churn) - Telecom X

Este proyecto realiza un análisis completo de datos de clientes para identificar patrones y factores que influyen en la **evasión de clientes (churn)** en una empresa de telecomunicaciones.  
Incluye desde la carga y limpieza de datos, hasta visualizaciones y análisis de correlaciones, con el objetivo de generar **insights accionables** para reducir la tasa de baja de clientes.

---

## 📌 Contenido del Proyecto

1. **Carga de datos**  
   - Importación de dataset desde archivo CSV o API.
   - Exploración inicial de la estructura y tipos de datos.

2. **Limpieza y Tratamiento**  
   - Detección y tratamiento de valores nulos.
   - Eliminación de duplicados.
   - Corrección de inconsistencias en variables categóricas y numéricas.

3. **Creación de Variables**  
   - Cálculo de `Cuentas_Diarias` a partir de la facturación mensual.
   - Creación de `TotalServices` para analizar el número de servicios contratados.

4. **Estandarización de Datos** *(opcional)*  
   - Conversión de valores textuales a binarios (Ej: Sí/No → 1/0).
   - Renombrado de columnas para mayor claridad.

5. **Análisis Exploratorio de Datos (EDA)**  
   - Análisis descriptivo (media, mediana, desviación estándar).
   - Distribución de Churn.
   - Relación de Churn con variables categóricas y numéricas.
   - Visualizaciones con `Matplotlib` y `Seaborn`.

6. **Correlaciones (Extra)**  
   - Matriz de correlación.
   - Relación entre `Cuentas_Diarias`, `TotalServices` y Churn.

7. **Informe Final**  
   - Introducción.
   - Proceso de limpieza y tratamiento.
   - Resultados del EDA.
   - Conclusiones e Insights.
   - Recomendaciones estratégicas.
