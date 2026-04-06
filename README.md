Análisis de Ventas y Rendimiento Comercial

Descripción del Proyecto
Este proyecto analiza el rendimiento de ventas de una empresa para comprender el comportamiento del pipeline comercial, identificar los productos más rentables, evaluar el desempeño del equipo de ventas y detectar patrones temporales en las ventas.
El objetivo es generar insights accionables que permitan optimizar la estrategia comercial y mejorar la conversión de oportunidades en ingresos reales.

Objetivos
•	Analizar el rendimiento general de ventas 
•	Identificar productos que generan mayor revenue 
•	Evaluar el desempeño del equipo de ventas 
•	Analizar la tasa de conversión (Win Rate) 
•	Detectar patrones temporales en las ventas 
•	Determinar factores que influyen en el cierre de deals 

Herramientas y Tecnologías
•	Excel (Power Query & Power Pivot) → Limpieza, modelado y DAX 
•	Python (Pandas) → Análisis exploratorio y validación de hipótesis 
•	Power BI → Visualización, dashboard y storytelling 

Dataset
El análisis se basa en cuatro tablas principales:
•	sales_pipeline → Información de oportunidades, etapas y revenue 
•	accounts → Datos de clientes (industria, tamaño, ubicación) 
•	products → Información de productos 
•	sales_teams → Datos del equipo comercial 


Procesamiento de Datos (Power Query)

Se construyó un pipeline estructurado:
1. Limpieza de datos
•	Manejo de valores nulos (ej. Unknown account) 
•	Estandarización de nombres (ej. GTXPro → GTX pro) 
•	Conversión de tipos de datos 

2. Modelado de datos
•	Creación de Star Schema: 
o	Fact Table → Sales 
o	Dimensiones → Accounts, Products, Agents, Date 

3. Feature Engineering
•	Creación de deal_size (Small / Large) 
•	Creación de tabla de fechas (DimDate) 
•	Cálculo de duración de deals 

Análisis en Python
•	Análisis exploratorio (EDA) 
•	Validación de calidad de datos 
•	Pruebas de hipótesis: 

Hipótesis analizadas:
•	H1: Demanda del producto 
•	H2: Adopción por industria 
•	H3: Rendimiento del equipo de ventas 
•	H4: Impacto del tamaño del deal 
•	H5: Patrones temporales 

Dashboards en Power BI

1. Executive Overview
•	KPIs: 
o	Revenue Won 
o	Total Deals 
o	Win Rate 
o	Avg Deal Size 
•	Tendencia temporal de revenue 

2. Product Analysis
•	Revenue por producto 
•	Win Rate por producto 

3. Customer / Sector Analysis
•	Revenue por industria 
•	Identificación de sectores más rentables 

4. Sales Team Performance
•	Revenue por vendedor 
•	Win Rate por agente 
•	Identificación de top performers 

5. Deal Size Analysis
•	Comparación entre: 
o	Revenue 
o	Win Rate 
•	Análisis del impacto del tamaño del trato 


Insights Principales
•	GTX Pro es el principal generador de revenue 
•	GTX Basic domina en volumen de oportunidades 
•	Existen diferencias claras en desempeño del equipo 
•	El negocio depende principalmente de deals pequeños 
•	Las ventas presentan patrones cíclicos 

Recomendaciones de Negocio
•	Priorizar productos de alto valor (GTX Pro) 
•	Optimizar conversión en productos de volumen 
•	Replicar estrategias de top performers 
•	Incrementar enfoque en deals grandes 
•	Alinear estrategias con ciclos de demanda 

Future Improvements
•	Integrar más variables (descuentos, duración del ciclo) 
•	Implementar modelos predictivos 
•	Segmentar clientes de forma avanzada 
•	Optimizar el pipeline de ventas 
•	Automatizar actualización de datos 

Conclusión

Este proyecto demuestra un flujo completo de análisis:
•	Limpieza y transformación de datos 
•	Modelado con esquema estrella 
•	Análisis exploratorio y validación en Python 
•	Creación de métricas con DAX 
•	Desarrollo de dashboards en Power BI 
Mostrando cómo los datos pueden utilizarse para impulsar decisiones estratégicas en el área comercial.

 Autor
Joan Garcia

