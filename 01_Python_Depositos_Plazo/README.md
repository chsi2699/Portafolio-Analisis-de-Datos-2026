# Proyecto 1 — Python: Depósitos a plazo en Chile

## 1. Objetivo

Analizar y visualizar la evolución del número de depósitos a plazo en Chile mediante Python y Google Colab, identificando tendencias, fluctuaciones y cambios relevantes a lo largo del tiempo.

## 2. Descripción de los datos

- **Serie:** Tenencia, número y monto de depósitos a plazo por género.
- **Código:** F022.DPZA.STO.Z.Z.N.M
- **Institución de referencia:** Comisión para el Mercado Financiero (CMF).
- **Período analizado:** 2009–2026.
- **Frecuencia:** Mensual.
- **Unidad:** Número de depósitos a plazo vigentes.
- **Archivo utilizado:** `Num_depositos_a_plazo.xlsx`.

## 3. Herramientas y metodología

Se utilizó Google Colab con Python y las bibliotecas pandas, NumPy, matplotlib y seaborn.

El procedimiento consistió en cargar el archivo Excel, explorar los registros, verificar los tipos de datos y los valores faltantes, preparar la columna de fechas, ordenar cronológicamente las observaciones y construir un gráfico de líneas.

## 4. Principales hallazgos

La serie presenta una tendencia general creciente entre 2009 y 2026.

El aumento más pronunciado se observa durante 2022–2023, cuando el número de depósitos superó los 2,5 millones. Este comportamiento podría relacionarse con el aumento de las tasas de interés durante el período inflacionario, aunque el análisis descriptivo no permite establecer una relación causal.

Desde 2024 se observa una corrección y posterior estabilización en torno a los 2,2 millones de depósitos.

## 5. Archivos del proyecto

- `Andara_Jesús_Reporte1 (1).ipynb`: código, gráfico e interpretación.
- `Num_depositos_a_plazo.xlsx`: base de datos utilizada.

## 6. Instrucciones de ejecución

1. Abrir Google Colab.
2. Cargar el archivo `.ipynb` del proyecto.
3. Subir `Num_depositos_a_plazo.xlsx` a la carpeta `sample_data` de Colab.
4. Seleccionar **Entorno de ejecución → Ejecutar todo**.
5. Revisar la exploración, el gráfico y la interpretación final.

**Nota:** El notebook utiliza la ruta `/content/sample_data/Num_depositos_a_plazo.xlsx`, por lo que el archivo Excel debe encontrarse en esa ubicación antes de ejecutar el código.

---

Proyecto académico desarrollado para Herramientas Avanzadas de Análisis de Datos, Universidad del Desarrollo, segundo semestre de 2026.
