# Análisis de Datos Financieros con Python

Este proyecto consiste en la integración, análisis y visualización de datos financieros usando Python. Se utilizaron dos fuentes de datos: un archivo CSV con información de clientes y una base de datos SQLite con transacciones bancarias. El objetivo fue combinar ambos conjuntos, limpiar los datos y generar visualizaciones interactivas.

## Librerías Utilizadas

- **Pandas**: Para la carga, limpieza y análisis de datos.
- **SQLite3**: Para conectarse a la base de datos y extraer datos desde una tabla.
- **Bokeh**: Para generar visualizaciones interactivas.
- **Jupyter Notebook**: Para desarrollar y documentar el análisis paso a paso.

## Qué se hizo

1. Se cargó el CSV y la base de datos SQLite.
2. Se realizó un merge entre los datos usando el campo `Customer Id`.
3. Se limpiaron columnas, se transformaron tipos de datos y se agregaron nuevas variables como el mes.
4. Se agruparon los datos para obtener depósitos, retiros y saldos por cliente.
5. Se generaron gráficos interactivos con Bokeh para visualizar los resultados.

## Los datasets se extrajeron de los siguientes enlaces 
1. Para los datos de transacciones bancarias: https://excelbianalytics.com/wp/downloads-20-sample-csv-files-data-sets-for-testing-till-2-million-records-bank-transactions/
2. Para los datos de clientes: https://github.com/datablist/sample-csv-files/blob/main/README.md

