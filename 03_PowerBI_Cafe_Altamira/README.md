# Proyecto 3 — Power BI: Análisis comercial de Café Altamira

## 1. Objetivo

Analizar el desempeño comercial de Café Altamira entre enero de 2024 y diciembre de 2025 mediante Power BI, identificando problemas de ventas, oportunidades de crecimiento y productos con baja rentabilidad.

## 2. Descripción de los datos

- **Empresa:** Café Altamira.
- **Período analizado:** Enero de 2024 – diciembre de 2025.
- **Frecuencia de análisis:** Mensual.
- **Registros de ventas:** 4.648.
- **Tablas originales:** Ventas, Productos y Sucursales.
- **Herramienta:** Microsoft Power BI Desktop.
- **Archivo del proyecto:** `Caso_01_Andara.pbix`.

Los datos corresponden a un caso académico de ventas de una cadena de cafeterías.

## 3. Herramientas y metodología

El análisis se realizó utilizando Power BI, Power Query y DAX.

El procedimiento incluyó:

1. **Limpieza de datos:** revisión de tipos de datos, formatos, nombres de categorías y consistencia de los registros mediante Power Query.
2. **Modelo de datos:** construcción de un modelo estrella, utilizando Ventas como tabla de hechos y Productos, Sucursales y Calendario como dimensiones.
3. **Cálculos:** creación de medidas DAX para ventas totales, número de ventas, ticket promedio y margen porcentual.
4. **Visualizaciones:** elaboración de un reporte interactivo con indicadores, gráficos, tablas y filtros.

Se construyeron dos páginas: Resumen ejecutivo y Análisis comercial.

## 4. Principales indicadores

Durante el período analizado se obtuvieron los siguientes resultados:

- **Ventas totales:** $27.036.860.
- **Número de ventas:** 4.648.
- **Ticket promedio:** $5.816,88.
- **Margen bruto:** 39,45 %.

## 5. Principales hallazgos

### 5.1. Problemas de ventas en Las Condes

La sucursal Las Condes registró una disminución importante de sus ventas entre mayo y julio de 2025.

Durante ese período vendió $307.370, frente a $803.350 en los mismos meses de 2024, lo que representa una caída del **61,74 %**.

Se recomienda investigar las causas de esta disminución.

### 5.2. Producto con altas ventas y baja rentabilidad

Mocaccino fue el producto con mayores ingresos acumulados, alcanzando **$4.029.300**.

Sin embargo, presentó un margen bruto de apenas **6,72 %**, considerablemente inferior al margen general de la empresa (39,45 %).

Esto sugiere revisar sus costos, precios y descuentos.

### 5.3. Categoría con mayor crecimiento

Bebidas Frías fue la categoría con mayor crecimiento porcentual entre 2024 y 2025.

Sus ventas aumentaron de $2.106.810 a $2.823.900, equivalentes a un crecimiento del **34,04 %**.

Este resultado representa una oportunidad de desarrollo comercial.

## 6. Recomendación gerencial

Se recomienda priorizar tres acciones:

1. Analizar las causas de la disminución de ventas en Las Condes.
2. Revisar la estructura de costos y precios del Mocaccino para mejorar su rentabilidad.
3. Evaluar oportunidades para potenciar Bebidas Frías, considerando su crecimiento durante 2025.

## 7. Archivos del proyecto

- `Caso_01_Andara.pbix`: archivo de Power BI con los datos importados, el modelo, las medidas DAX y el reporte interactivo.

## 8. Instrucciones de uso

1. Tener instalado Microsoft Power BI Desktop.
2. Descargar el archivo `.pbix` desde este repositorio.
3. Abrirlo con Power BI Desktop.
4. Seleccionar las páginas **Resumen ejecutivo** y **Análisis comercial**.
5. Utilizar los filtros de año y sucursal para explorar los resultados.
6. Revisar los indicadores, las visualizaciones y las conclusiones comerciales.

El archivo contiene el modelo de datos utilizado para el análisis.

---

Proyecto académico desarrollado para Herramientas Avanzadas de Análisis de Datos, Universidad del Desarrollo, segundo semestre de 2026.
