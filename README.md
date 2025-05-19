# Análisis de datos - Informe prueba analista II con Streamlit
Este proyecto es una aplicación web interactiva para análisis y visualización de movimientos y saldos financieros, desarrollada con Streamlit y pandas.

## Requisitos
- Python 3.7 o superior
- Librerías: `streamlit`, `pandas`, `numpy`, `matplotlib`, `seaborn`

Puedes instalar las librerías necesarias con:

```
pip install streamlit pandas numpy matplotlib seaborn
```

## Archivos necesarios

- Archivo Excel con las hojas `movimientos` y `saldos` en la ruta especificada en el código (`file_path`).
- Imagen para el banner en la ruta configurada (`st.image`).

## Cómo ejecutar

1. Coloca el archivo Excel con los datos en la ruta indicada o modifica la variable `file_path` en el código para apuntar al archivo correcto.

2. En consola, desde la carpeta del proyecto, ejecuta:

```
streamlit run nombre_de_tu_script.py
```

3. Se abrirá una pestaña en tu navegador con la aplicación.

## Funcionalidades

- Filtros por rango de fechas, negocio y cuenta.
- Visualización de estadísticas generales.
- Gráficos de evolución temporal, top cuentas y negocios por movimientos y saldos.
- Detección de anomalías en movimientos y saldos.
- Comparación entre dos periodos seleccionados.
- Análisis cruzado y correlación entre flujo neto y saldo.
- Identificación de riesgos financieros (saldos negativos).

---

*Por Paula Cadena Valencia*
