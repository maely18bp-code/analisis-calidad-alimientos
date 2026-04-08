# 📊 Análisis de Calidad de Alimentos

## 📌 Problema de negocio
Una empresa de distribución alimentaria ha detectado incidencias en la calidad de sus productos.  
El objetivo de este análisis es identificar patrones de riesgo relacionados con temperatura y manipulación para reducir pérdidas y mejorar la seguridad alimentaria.

---

## 🎯 Objetivos
- Analizar incidencias por producto  
- Evaluar riesgos asociados a la temperatura  
- Detectar patrones operativos  
- Proponer acciones correctivas basadas en datos  

---

## 📂 Dataset
El dataset contiene información sobre:

- Fecha  
- Producto (Pescado, Carne, Pollo)  
- Temperatura  
- Lote  
- Incidencia  
- Tipo de problema  

---

## 🧹 Limpieza de datos
- Conversión de fechas a formato datetime  
- Validación de valores nulos  
- Estandarización de variables  

---

## 📊 Análisis realizado
- Análisis de incidencias por producto  
- Relación entre tipo de problema y producto  
- Evaluación de temperatura promedio  
- Análisis temporal de incidencias  
- Clasificación de riesgo por temperatura  

---

## 📈 Visualizaciones
Se desarrollaron gráficos para identificar:
- Distribución de incidencias por producto  
- Relación entre producto y tipo de problema  
- Estado de temperatura por producto  

---

## 🔍 Insights clave
- Las incidencias son constantes en el tiempo, indicando fallos estructurales  
- El pescado presenta inestabilidad térmica (riesgo latente)  
- La carne combina temperatura fuera de rango y contaminación (mayor riesgo sanitario)  
- El pollo muestra un patrón creciente de incidencias  

---

## 🧠 Interpretación estratégica
El análisis evidencia que los problemas no son aislados, sino parte de un fallo continuo en los procesos operativos.  
Esto sugiere la necesidad de mejorar controles diarios en lugar de actuar solo ante incidentes puntuales.

---

## ✅ Recomendaciones
- Priorizar controles de higiene en carne  
- Mejorar la cadena de frío en pescado  
- Supervisar el almacenamiento progresivo en pollo  
- Implementar monitoreo continuo de temperatura  

---

## 🚀 Posibles mejoras futuras
- Integrar datos de transporte para analizar la cadena de frío completa  
- Implementar alertas automáticas de temperatura  
- Analizar tiempos de almacenamiento por lote  

---

## 🛠️ Tecnologías utilizadas
- Python  
- Pandas  
- Matplotlib  

---

## 📁 Estructura del proyecto
analisis_calidad_alimentos/

│

├── data/

│ └── calidad_alimentos.csv

│

├── notebooks/

│ └── analisis.ipynb

│

└── README.md
