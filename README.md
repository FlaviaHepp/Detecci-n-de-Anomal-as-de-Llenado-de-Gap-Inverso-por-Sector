# 📉📊Detección de Anomalías de Llenado de Gap Inverso por Sector

## 📌Descripción del proyecto

Este proyecto implementa una consulta SQL para detectar anomalías en el llenado inverso de gaps de precios, segmentando el análisis por sector económico.

El objetivo es identificar comportamientos atípicos en la dinámica de precios, donde los gaps no se corrigen según el patrón esperado, lo que puede indicar:
- Cambios estructurales de tendencia
- Debilidad o fortaleza sectorial
- Distorsiones de mercado
- Eventos exógenos con impacto diferencial

## 🎯Objetivos del proyecto

- Detectar gaps de precios relevantes.
- Analizar el llenado inverso del gap en el tiempo.
- Comparar patrones entre distintos sectores.
- Identificar anomalías frente al comportamiento histórico.
- Automatizar análisis técnico avanzado mediante SQL.

## 🏦Contexto financiero

En análisis técnico, un gap representa una discontinuidad en el precio entre sesiones.
El llenado del gap suele interpretarse como una corrección natural del mercado.

📌 Cuando el gap:

- No se llena
- Se llena parcialmente
- O se llena en dirección inversa
- puede estar señalando anomalías relevantes, especialmente cuando el comportamiento difiere entre sectores.

Este tipo de análisis es clave para:
- Trading cuantitativo
- Research financiero
- Gestión de carteras
- Detección temprana de cambios de régimen

## 🧠Lógica del análisis

La consulta SQL:
- Identifica gaps de precios por activo.
- Clasifica gaps según dirección (alcista / bajista).
- Analiza el comportamiento posterior del precio.
- Detecta casos de llenado inverso o incompleto.
- Agrupa y compara resultados por sector.
- Marca anomalías cuando el patrón difiere del histórico sectorial.

📌 La lógica es extensible a distintos activos y horizontes temporales.

## 📊Ejemplos de anomalías detectadas

- Sectores donde los gaps no se corrigen históricamente.
- Gaps que se llenan en dirección contraria a lo esperado.
- Diferencias sectoriales en la velocidad de corrección.
- Señales tempranas de debilidad o fortaleza relativa.

## 🛠️Tecnologías utilizadas

SQL

Compatible con:
- PostgreSQL
- BigQuery
- SQL Server
- Oracle
- MySQL (con ajustes menores)

## 📁Estructura del proyecto

├── anomalia_de_llenado_de_gap-inversa_por_sector.sql
└── README.md

## ▶️Cómo utilizar la consulta

Abrir el archivo anomalia_de_llenado_de_gap-inversa_por_sector.sql.

Configurar:
- Tabla de precios
- Identificación de gaps
- Clasificación sectorial
- Ventana temporal de análisis
- Ejecutar la consulta en el motor SQL.
- Analizar resultados o integrarlos en dashboards financieros.

## 🚀Posibles extensiones

- Medir tiempo promedio de llenado del gap.
- Incorporar volumen y volatilidad.
- Comparar con benchmarks de mercado.
- Generar alertas automáticas por sector.
- Integrar con modelos predictivos de tendencia.

## 👤Autora

Flavia Hepp
Proyecto de SQL aplicado a análisis técnico avanzado y detección de anomalías financieras.
