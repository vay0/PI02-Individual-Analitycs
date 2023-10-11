# PI02-Individual-Analitycs
![image](https://github.com/vay0/PI02-Individual-Analitycs/assets/105746281/9d3c0c20-156a-4309-abb7-e7bbeabac317)

# Proyecto de Análisis de Datos para la Organización de Aviación Civil Internacional (OACI)
En este Proyecto Integral (PI), asumo el rol de analista de datos, encargado por la Organización de Aviación Civil Internacional (OACI), para llevar a cabo un análisis de datos con el objetivo de generar información relevante.

## Archivos del Repositorio

- **AccidentesAviones.csv:** Dataset original.
- **Análisis exploratorio.ipynb:** Notebook que contiene el análisis de datos realizado, junto con sus respectivas conclusiones.
- **KPI.ipynb:** Notebook que proporciona los datos necesarios para la visualización de los KPIs en el dashboard.
- **tripulacion.xlsx:** Archivo de Excel para KPI 1 (Tasa de fatalidad de tripulantes).
- **Total.xlsx:** Archivo de Excel para KPI 2 (Tasa de fallecidos).
- **Df_accidentes_analisis:** Dataset con los datos transformados para el dashboard.

## Conclusiones

Durante el análisis de datos, se llegaron a las siguientes conclusiones:

- La variable "hora declarada" no parece tener relación con las otras variables numéricas.
- La variable "all_aboard" está relacionada con las variables "crew_aboard", "pasajeros a bordo", "cantidad de fallecidos", "crew fatalities", "passenger fatalities" y "ground". Esto se debe a que todas estas variables están relacionadas con las personas involucradas en los accidentes.
- La cantidad de personas que viajaban en estos vuelos oscilaba entre 2 y 200 aproximadamente.
- Hubo un número muy reducido de personas que murieron en tierra.
- Aproximadamente la mitad de las personas a bordo fallecieron.
- La variable "pasajeros a bordo" está correlacionada al 100% con "all_aboard", ya que esta última representa la cantidad total de personas a bordo, incluyendo a los pasajeros.
- La "cantidad de fallecidos" está correlacionada en un 99% con "passenger fatalities".
