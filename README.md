# Análisis de Proyección de Riesgos - Paigo

Este repositorio contiene el análisis de cartera y la evaluación de riesgos crediticios realizado para Paigo. El proyecto utiliza técnicas de análisis de datos y consultas SQL para identificar patrones de morosidad, segmentar clientes y proponer estrategias accionables de mitigación.

## 🚀 Descripción del Proyecto
El objetivo principal es transformar los datos transaccionales de la cartera en insights de negocio. A través de la carga y procesamiento de datasets, se ha logrado reclasificar estados de mora, analizar el impacto geográfico del riesgo y segmentar el comportamiento de los clientes para mejorar la toma de decisiones.

## 🛠 Tecnologías Utilizadas
* Python: Procesamiento de datos y manipulación de DataFrames.
* Pandas: Limpieza y estructuración de datos.
* DuckDB: Motor SQL integrado para consultas analíticas de alto rendimiento.
* Matplotlib / Seaborn: Visualización de datos.

## 📂 Estructura del Repositorio
ANALISTA-DE-PROYECCION-DE-RIESGO/
├── data/raw/              # Archivos fuente de la cartera y pagos.
├── docs/                  # Documentación técnica y estratégica (PDFs).
├── notebooks/             # Notebooks de análisis y validación.
│   ├── 01_calidad_datos.ipynb
│   └── 02_sql_analitico.ipynb
├── reports/figures/       # Visualizaciones finales y reportes.
└── README.md

## 📊 Principales Hallazgos
1. Concentración Geográfica (Uruguay): Ticket promedio de mora significativamente superior a otros mercados.
2. Segmentación Premium vs. Nuevos: Diferenciación en velocidad de respuesta; se proponen estrategias de cobranza distintas para cada grupo.
3. Accionabilidad: Recomendaciones claras para el equipo de cobranzas y recalibración de políticas de admisión.

## Visualización de Resultados

### Capital en Riesgo por País
![Capital en riesgo por país](reports/figures/capital_en_riesgo_pais.png)

### Distribución del Riesgo por Segmento
![Riesgo por segmento](reports/figures/riesgo_por_segmento.png)

## 📄 Metodología de Validación
Se aplicó auditoría de datos comparando métricas SQL con registros reales, apoyándose en herramientas de IA para interpretación y redacción, siempre bajo validación humana.