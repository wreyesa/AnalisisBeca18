# Concurso Beca 18 - 2025

## Contexto
PRONABEC es una institución pública que se dedica en reducir la brecha educativa y garantizar acceso a la educación superior a través de becas o créditos educativos, en este caso, se utilizan los resultados de la etapa de preselección del programa Beca 18 Convocatoria 2025.

## Descripción
En este proyecto se realiza la lectura y análisis de la lista de los postulantes preseleccionados de Beca 18. Esto se divide en dos partes, la primera en el archivo "transform.ipynb" donde se realiza la lectura, transformación y limpieza de la lista de postulantes de 30 páginas de un PDF. También, se emplea principalmente las librerías de camelon y pandas para leer y manipular los datos. Algunas actividades que se realizan son: eliminar filas no deseadas, eliminar columnas no necesarias, eliminar filas con datos faltantes, etc. Además, se exportan los siguientes archivos: data.csv, modalidades.csv y regiones.csv.

En el segundo archivo "analysis.ipynb" se analiza los resultados de la etapa de preselección a nivel de región, modalidad y demanda global utilizando el archivo data.csv. En este caso, se utilizan adicionalmente las librerias de matplotlib y seaborn para desplegar algunas visualizaciones de los resultados. El análisis se aborda en los siguientes puntos:
* Cantidad de postulantes por Región
* Cantidad de postulantes por Modalidad de Beca
* Cantidad de Postulantes por Región y Modalidad
* Oferta y Demanda
* Distribución general del puntaje del examen
* Distribución del puntaje del examen por modalidad de beca
* Distribución del puntaje del examen por región

## Hallazgos
Algunos hallazgos que se destacan son:
* El porcentaje de postulantes preseleccionados de Lima representa el 23.45% del total de regiones.
* Las 3 regiones con la mayor cantidad de postulantes provienen de Lima, Ayacucho y Cusco.

* La mayor parte postula a la categoría ORDINARIA que representa el 71.85% del total

* La categoria ORDINARIA es la más demandada en la mayoría de las regiones. Excepto en Ayacucho y Loreto, donde la categoría CNA y PA presenta la mayor cantidad de postulantes.
* La segunda modalidad de beca más demandada es CNA Y PA o REPARED.

* En la mayoría de regiones la demanda se distribuye entre 5 a 7 modalidades de beca.

* En la Beca FF.AA., todos los preseleccionados accederían a una de estas becas integrales suponiendo que presentan la carta de ingreso a una IES. Este es el apartado donde aparece una pregunta ¿qué sucede con las 130 (560-430) becas adicionales de esta modalidad suponiendo que las 430 becas ya estarían asignadas a un postulante? ¿Se distribuye estas becas para otras modalidades? ¿Cómo se aborda está situación?
* De la misma forma, en la Beca Protección todos los preseleccionados de esta modalidad accederían a una de estas becas integrales. ¿Qué sucede con estas 358 (460-102) becas adicionales de esta modalidad?

* El puntaje adicional aumenta signficativamente el desempeño final del postulante, lo cual garantiza una mayor probabilidad de acceder a una de las becas del concurso.
* El mayor puntaje adicional fue de 35 puntos, el cual fue asignado a dos postulantes bajo la modalidad de EIB.
