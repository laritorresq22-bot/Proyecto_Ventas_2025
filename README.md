# Proyecto_Ventas_2025


**Objetivo:** Analizar las ventas por región y canal para detectar patrones, cuellos de botella y oportunidades.

|TEST|

## Datos
- **Fuente:** `data/raw/ventas.xlsx` (hojas: `2024`, `2025`)
- **Tamaño aproximado:** 20k filas
- **Descripción rápida:** Fecha, producto, canal, región, unidades, ingreso


## Metodología
1. Limpieza de datos (`src/limpieza.py`): valores nulos, duplicados, tipado de columnas
2. Análisis exploratorio (`notebooks/01_exploracion.ipynb`): tendencias, outliers, estacionalidad
3. Métricas clave: ingresos, margen, tasa de devolución, ticket medio
4. Visualización: dashboard con ventas por región y canal


## Resultados (resumen)
- Región Norte: +12% YoY
- Canal Online: mayor crecimiento; foco en upselling
- Productos X e Y concentran 60% del ingreso


## Cómo reproducir
1. Clona o descarga este repo
2. Crea entorno (opcional) y ejecuta notebooks de `notebooks/`
3. Revisa `reports/` para ver el informe final


## Autora
Lara — Estudiante de Data Analytics (Pontia Tech)
