# Proyecto 4 — Tableau: Ventas y rentabilidad de Café Altamira

## 1. Objetivo

Analizar la evolución de las ventas y la rentabilidad de Café Altamira entre enero de 2024 y diciembre de 2025 mediante Tableau, identificando las categorías y sucursales que más contribuyeron al desempeño comercial.

## 2. Descripción de los datos

- **Empresa:** Café Altamira.
- **Período analizado:** Enero de 2024 – diciembre de 2025.
- **Frecuencia de análisis:** Mensual.
- **Registros de ventas:** 4.648.
- **Estructura:** Una sábana de datos con información de ventas, productos y sucursales.
- **Herramienta:** Tableau.
- **Archivo del proyecto:** `Caso_01_Andara_Tableau.twbx`.

Los datos corresponden a un caso académico de ventas de una cadena de cafeterías.

## 3. Herramientas y metodología

El análisis se realizó utilizando Tableau y campos calculados.

El procedimiento incluyó:

1. **Revisión de datos:** verificación de los tipos de datos, fechas, valores numéricos e identificadores de venta.
2. **Normalización de categorías:** creación del campo `Categoría corregida` para unificar diferencias de escritura, mayúsculas y acentos.
3. **Cálculo de indicadores:** creación de cuatro medidas para evaluar las ventas y la rentabilidad.
4. **Visualización:** elaboración de gráficos de evolución mensual, ventas por categoría, utilidad bruta por categoría y ventas por sucursal.
5. **Interactividad:** incorporación de filtros de Año y Sucursal que actualizan los indicadores y gráficos del dashboard.

## 4. Principales indicadores

Durante el período analizado se obtuvieron los siguientes resultados:

- **Ventas totales:** $27.036.860.
- **Costo de ventas:** $16.370.370.
- **Utilidad bruta:** $10.666.490.
- **Margen bruto:** 39,45 %.

Los indicadores se calcularon utilizando las siguientes relaciones:

- **Ventas:** suma de Cantidad × Precio Unitario.
- **Costo de ventas:** suma de Cantidad × Costo Unitario Venta.
- **Utilidad bruta:** Ventas − Costo de ventas.
- **Margen bruto:** (Utilidad bruta / Ventas) × 100.

## 5. Principales hallazgos

### 5.1. Evolución de las ventas

Las ventas aumentaron de $13.114.640 en 2024 a $13.922.220 en 2025, lo que representa un crecimiento del **6,16 %**.

Esto refleja una mejora general en los ingresos de la empresa durante el período analizado.

### 5.2. Diferencias entre ventas y rentabilidad

Bebidas Calientes fue la categoría con mayores ventas acumuladas, alcanzando **$8.741.730**.

Sin embargo, Pastelería generó la mayor utilidad bruta, con **$3.620.120**.

Este resultado demuestra que la categoría que genera mayores ingresos no necesariamente es la que aporta más utilidad al negocio.

### 5.3. Desempeño de las sucursales

Las Condes registró las mayores ventas acumuladas, con **$5.809.650**.

No obstante, sus ventas disminuyeron un **9,73 %** entre 2024 y 2025.

En contraste, Rancagua Plaza aumentó sus ventas aproximadamente un **20,31 %** durante el mismo período.

Estos resultados muestran diferencias importantes en el desempeño comercial de las sucursales.

## 6. Recomendación gerencial

Se recomienda potenciar la categoría Pastelería por su contribución a la utilidad bruta, revisar la estructura de costos y precios de Bebidas Calientes e investigar las causas de la disminución de ventas en Las Condes.

Asimismo, resulta conveniente analizar las prácticas comerciales de Rancagua Plaza para identificar oportunidades de mejora aplicables a otras sucursales.

## 7. Archivos del proyecto

- `Caso_01_Andara_Tableau.twbx`: libro de trabajo empaquetado de Tableau, que incluye los datos utilizados, campos calculados, visualizaciones y dashboard interactivo.

## 8. Instrucciones de uso

1. Tener instalado Tableau Desktop o una versión compatible de Tableau.
2. Descargar el archivo `.twbx` desde este repositorio.
3. Abrir el archivo con Tableau.
4. Acceder al dashboard **Café Altamira**.
5. Utilizar los filtros de Año y Sucursal para explorar los resultados.
6. Revisar los cuatro indicadores y los gráficos comparativos.

Al tratarse de un libro empaquetado (`.twbx`), el archivo incorpora los datos utilizados para construir las visualizaciones.

---

Proyecto académico desarrollado para Herramientas Avanzadas de Análisis de Datos, Universidad del Desarrollo, segundo semestre de 2026.
