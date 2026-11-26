# Proyecto 2 — R: Índice de precios de alimentos

## 1. Objetivo

Analizar la evolución del índice de precios de alimentos mediante R y Google Colab, identificando tendencias, fluctuaciones, máximos, mínimos y posibles patrones estacionales.

## 2. Descripción de los datos

- **Serie:** Índice de precios de alimentos — Productos básicos total.
- **Código:** F019.PPBA.INP.46T.M.
- **Fuente:** Organización de las Naciones Unidas para la Alimentación y la Agricultura (FAO).
- **Período analizado:** Enero de 2010 – agosto de 2026.
- **Frecuencia:** Mensual.
- **Unidad:** Índice, con base 2014–2016 = 100.
- **Archivo utilizado:** `EI_PROD_BAS_AL (Productos basicos total).xlsx`.

## 3. Herramientas y metodología

El análisis se realizó en Google Colab utilizando R y las bibliotecas readxl, dplyr, ggplot2, scales y tidyr.

Primero se importó la hoja `Cuadro` del archivo Excel y se prepararon las fechas y los valores del índice.

Posteriormente, se elaboraron tres visualizaciones:

1. **Serie temporal y promedio móvil de 12 meses:** permite observar la tendencia general y suavizar las fluctuaciones de corto plazo.
2. **Mapa de calor:** permite comparar los valores del índice entre años y meses, buscando posibles patrones estacionales.
3. **Variación porcentual interanual:** mide el cambio porcentual respecto del mismo mes del año anterior.

Como la variable es un índice, la variación interanual se calculó mediante:

**Variación 12 meses = (Índice actual / Índice de hace 12 meses − 1) × 100.**

## 4. Principales hallazgos

El índice presenta fluctuaciones importantes durante el período analizado, con un promedio aproximado de **113,9 puntos**.

El máximo se registró en **marzo de 2022 (160,2 puntos)**, coincidiendo con un período de fuertes perturbaciones en los mercados internacionales de alimentos.

El mínimo corresponde a **enero de 2016 (84,9 puntos)**.

En agosto de 2026, el índice alcanzó **133,3 puntos**, ubicándose por encima del promedio histórico de la muestra. Su variación interanual fue aproximadamente **+2,5 %**.

El mapa de calor no permite identificar una estacionalidad mensual claramente marcada. En cambio, destacan los cambios de nivel entre distintos períodos económicos.

Estos resultados muestran la utilidad de combinar visualizaciones temporales para distinguir tendencias, fluctuaciones y variaciones interanuales.

## 5. Archivos del proyecto

- `Andara_productos_basicos_total (2) (1).ipynb`: notebook con código R, gráficos e interpretación económica.
- `EI_PROD_BAS_AL (Productos basicos total).xlsx`: base de datos utilizada.

## 6. Instrucciones de ejecución

1. Abrir Google Colab.
2. Cargar el archivo `.ipynb` del proyecto.
3. Cambiar el entorno de ejecución al lenguaje **R**.
4. Subir el archivo Excel al panel de archivos de Colab.
5. Seleccionar **Entorno de ejecución → Ejecutar todo**.
6. Revisar los tres gráficos y la interpretación económica.

El notebook instala automáticamente los paquetes necesarios si no se encuentran disponibles.

**Nota:** El código busca un archivo Excel cuyo nombre comienza con `EI_PROD_BAS_AL`. Utiliza la hoja `Cuadro` y omite las dos primeras filas antes de procesar los datos.

Al finalizar, también genera tres gráficos en formato PNG, que pueden descargarse desde Colab.

---

Proyecto académico desarrollado para Herramientas Avanzadas de Análisis de Datos, Universidad del Desarrollo, segundo semestre de 2026.
