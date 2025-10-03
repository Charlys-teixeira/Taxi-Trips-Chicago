📌 Proyecto

Este proyecto es un análisis exploratorio de datos (EDA) y prueba de hipótesis aplicado a los datos de viajes en taxi en Chicago. El objetivo es entender los patrones de viaje, identificar los barrios más concurridos y verificar si factores externos (como el clima) afectan la duración de los viajes.

## 📂 Datos

Se utilizaron tres conjuntos de datos CSV:

- `project_sql_result_01.csv` – número de viajes por empresa de taxi (15–16 de noviembre de 2017)  
- `project_sql_result_04.csv` – barrios de destino y promedio de viajes en noviembre de 2017  
- `project_sql_result_07.csv` – viajes desde el Loop al Aeropuerto Internacional O'Hare, incluyendo fecha/hora, condiciones meteorológicas y duración del viaje  

## 🛠 Metodología

**Paso 4 – Análisis Exploratorio de Datos (EDA):**

- Importación e inspección de datos (pandas)  
- Verificación y corrección de tipos de datos  
- Identificación de los 10 barrios principales por número de viajes  
- Creación de gráficos:
  - Número de viajes por empresa de taxi  
  - Top 10 barrios por número de viajes  
- Interpretación y conclusiones basadas en los gráficos  

**Paso 5 – Prueba de Hipótesis:**

- Hipótesis probada:  
  "La duración promedio de los viajes desde el Loop al Aeropuerto Internacional O'Hare cambia los sábados lluviosos."  
- Pasos:
  - Formulación de la hipótesis nula (H₀) y alternativa (H₁)  
  - Definición del nivel de significancia (α = 0.05)  
  - Selección del test estadístico adecuado (t-test o Mann-Whitney según la distribución)  
  - Análisis del p-valor y decisión sobre H₀  
  - Interpretación de los resultados  

## 📊 Resultados Principales

- Las empresas de taxi más activas tuvieron un mayor volumen de viajes durante el período analizado  
- Los 10 barrios más populares mostraron concentración geográfica de destinos  
- La prueba de hipótesis indicó que las condiciones meteorológicas afectan la duración promedio de los viajes los sábados, proporcionando información valiosa para planificación logística y previsión de demanda  

## 🛠 Tecnologías Utilizadas

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy / Statsmodels  

## 💡 Conclusión

El proyecto demuestra habilidades en:  

- Manipulación y análisis de datos en Python  
- Visualización e interpretación de información  
- Prueba de hipótesis y estadística aplicada  
- Comunicación clara de resultados  
