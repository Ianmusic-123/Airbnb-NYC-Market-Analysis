# 🏙️ Airbnb NYC Market Analysis

## 📄 Descripción

Análisis de mercado sobre los listings de Airbnb en Nueva York, con datos reales
de 2019. El proyecto responde preguntas de pricing, distribución geográfica de la
oferta y comportamiento de hosts, para orientar decisiones de inversión y gestión
de propiedades en la plataforma.

## 🎯 Objetivos

- Limpiar y validar un dataset real de Kaggle, documentando cada decisión (nulos con significado real, outliers, valores inválidos).
- Responder preguntas de negocio mediante consultas equivalentes a SQL (`GROUP BY`, `HAVING`, *window functions*, subconsultas) implementadas con Pandas.
- Analizar la variación de precios por borough, barrio y tipo de habitación.
- Visualizar geoespacialmente la distribución de precios en la ciudad.
- Identificar patrones de comportamiento de hosts que operan múltiples listings.
- Traducir los hallazgos en recomendaciones para un inversionista o gestor de propiedades.

## 📊 Tecnologías y Librerías

- Python (3.x)
- pandas, numpy para manipulación y transformación de datos.
- matplotlib, seaborn para visualización, incluyendo un scatter geoespacial de precios.
- Streamlit para el dashboard interactivo con filtros por borough, tipo de habitación y rango de precio.
- Jupyter Notebook como entorno de análisis.

## ✅ Resultados Esperados

- **Análisis de pricing:** precio promedio y mediano por borough y tipo de habitación, con identificación de las zonas premium vs. las de mayor volumen de oferta.
- **Mapa geoespacial:** visualización de precios por coordenadas que reconstruye la silueta de la ciudad y expone visualmente los clústeres de precio alto.
- **Ranking de hosts:** identificación de operadores que gestionan múltiples listings dentro de cada borough.
- **Señales de calidad:** detección de hosts con alto volumen de listings pero bajo engagement de reseñas.
- **Dashboard interactivo:** exploración de todos los KPIs con filtros dinámicos, sin necesidad de tocar código.
