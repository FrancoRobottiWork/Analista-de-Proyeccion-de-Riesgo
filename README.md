# Análisis de Proyección de Riesgos - Paigo

Este repositorio contiene el análisis de cartera y la evaluación de riesgos crediticios realizado para Paigo. El proyecto utiliza técnicas de análisis de datos y consultas SQL para identificar patrones de morosidad, segmentar clientes y proponer estrategias accionables de mitigación.

## 🚀 Descripción del Proyecto
El objetivo principal es transformar los datos transaccionales de la cartera en **insights de negocio**. A través de la carga y procesamiento de datasets, se ha logrado reclasificar estados de mora, analizar el impacto geográfico del riesgo y segmentar el comportamiento de los clientes para mejorar la toma de decisiones.

## 🛠 Tecnologías Utilizadas
* **Python:** Para procesamiento de datos y manipulación de DataFrames.
* **Pandas:** Librería principal para la limpieza y estructuración de datos.
* **DuckDB:** Motor SQL integrado para consultas analíticas de alto rendimiento.
* **Matplotlib / Seaborn:** Visualización de datos.
* **OpenPyXL:** Manejo de archivos Excel.

## 📂 Estructura del Repositorio
* `/dataset`: Archivos fuente de la cartera y pagos.
* `SQL_analitico.ipynb`: Notebook principal de cálculo de riesgos y visualización.
* `consultas_calidad.ipynb`: Notebook de validación y reclasificación de mora.
* `insight accionables.pdf` & `uso de IA.pdf`: Documentación técnica y estratégica.

## 📊 Principales Hallazgos
1. **Concentración Geográfica (Uruguay):** Ticket promedio de mora significativamente superior a otros mercados.
2. **Segmentación Premium vs. Nuevos:** Diferenciación en velocidad de respuesta; se proponen estrategias de cobranza distintas para cada grupo.
3. **Accionabilidad:** Recomendaciones claras para el equipo de cobranzas y recalibración de políticas de admisión.

## Visualización de Resultados

### Capital en Riesgo por País
![Capital en riesgo por país](pictures/capital_en_riesgo_pais.png)

### Distribución del Riesgo por Segmento
![Riesgo por segmento](pictures/riesgo_por_segmento.png)

## 📄 Metodología de Validación
Se aplicó auditoría de datos comparando métricas SQL con registros reales, apoyándose en herramientas de IA para interpretación, siempre bajo validación humana.
