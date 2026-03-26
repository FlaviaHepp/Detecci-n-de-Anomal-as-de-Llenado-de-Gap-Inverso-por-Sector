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

***
📈🔥 **Cuando un gap alcista NO se cierra… y el volumen explota — algo grande está pasando**

Muchos traders esperan lo mismo después de earnings:

👉 “El gap se va a cerrar”

Pero… ¿qué pasa cuando ocurre exactamente lo contrario?

---

💡 Estuve analizando una anomalía muy interesante:

**El “llenado de gap inverso” a nivel sectorial**

---

🚀 **¿Qué detecta este insight?**

* 📊 Una empresa presenta un **gap alcista** tras ganancias
* ⛔ El precio NO retrocede (no hay pullback clásico)
* 🔥 El volumen **aumenta aún más en las siguientes 48h**

---

🧠 **¿Qué significa esto realmente?**

No es euforia minorista.

👉 Es una señal de **acumulación institucional**

* Compras sostenidas
* Validación del nuevo precio
* Cambio de percepción estructural

---

📊 Y cuando esto ocurre en múltiples empresas de un mismo sector…

💥 Estamos frente a un posible **cambio de régimen**

---

⚡ ¿Por qué es tan potente?

Porque rompe una de las “reglas” más repetidas del mercado:

❌ “Todos los gaps se cierran”
✅ *No cuando hay dinero fuerte entrando*

---

📈 Aplicaciones prácticas:

* Detectar sectores en fase de acumulación
* Identificar líderes tempranos post-earnings
* Evitar shorts en activos con demanda real
* Construir posiciones alineadas con institucionales

---

💬 Muchas veces el edge no está en el gap…
👉 está en lo que pasa DESPUÉS del gap.

---

En mercados reales, las anomalías suelen ser donde vive la oportunidad.

¿Sos de los que esperan siempre el cierre del gap… o mirás el volumen para confirmar? 👇
