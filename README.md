# ESTUDIO ESTADISTICO EN INGENIERIA ELECTRONICA

A partir de los resultados de la muestra tomada mediante una encuesta hecha a los estudiantes de ingeniería electronica de la Universidad del Magdalena podemos analizar de que manera equilibran su vida académica con su vida personal, considerando diferentes variables tanto cualitativas como cuantitativas y desarrollando un analisis descriptivo que busca comparar las realidades que hay dentro del programa y los resultados academicos generales de los estudiantes, mediante tablas de frecuencia, gráficos y medidas de tendencia, dispersión, forma y posición, por lo tanto, esta muestra resulta pertinente para comprender la realidad académica del grupo estudiado.

Para el proyecto se formula preguntas relevantes, se organiza y depura el conjunto de datos, se calculan tablas de frecuencia, gráficos, tendencia central, dispersión, forma y posición, se estima probabilidades empíricas cuando aportan contexto y se comunica resultados de manera clara y breve.

Este repositorio contiene los archivos generados durante el analisis descriptivo de la muestra.

## Archivos incluidos

- **Formulario original.pdf**: documento con el enlace utilizado para la recoleccion de los datos requeridos.
- **Base de datos de la muestra.csv**: base de datos sin identificadores con la informacion dada por medio de la encuesta, una fila por persona.
- **Diccionario categorico de las variables.xlsx**: diccionario de clasificacion de las variables utilizadas para el analisis (variable, etiqueta, tipo, unidades/categorías, valores válidos, reglas de NA).
- **Informe final_APA.pdf**: informe en formato APA que presenta el abstract, objetivos, método, resultados descriptivos, probabilidad empírica, discusión, limitaciones y referencias.
- **Presentación de los resultados.pdf**: presentación breve y ordenada del análisis que facilita su comprension.
- **Código utilizado para el análisis.html**: Codigo en HTML que muestra el resultado final de el proyecto a realizar.

## Requisitos 

Para la visualizacion de este es necesario contar con lo siguiente:
- Un navegador web moderno (Chrome, Firefox, Edge).
- R y RStudio (solo si se desea reproducir el análisis desde cero).
-Paquetes de R necesarios (según el .Rmd): tidyverse, readr, ggplot2, etc.
- Software para abrir: *CSV (Excel, LibreOffice o similar)*, *XLSX*, *PDF*

## Como reproducir el archivo HTML

El archivo en formato HTML contiene:

-  "< head >" con metadata (título, autores, fecha).
- Scripts de Pandoc para interacción interna.
- jQuery incluido por Pandoc.
- Contenido renderizado a partir del documento origen.
  
Esta estructuralizado de la siguiente manera:

1. EDAD (AGE)
2. PRESENCIA DE DISCAPACIDAD (DISC)
3. HORAS DE ESTUDIO (STDH)
4. LABURANTE (LAB)
5. PROMEDIO ACADEMICO (PM)
6. DISPONIBILIDAD DE PASATIEMPOS (PS)
7. SEMESTRE CON CANCELACIÓN DE MATERIAS (SC)
8. MATERIAS MATRICULADAS (MM)
9. SEMESTRES ACTIVO EN EL PROGRAMA (SA)
10. NUMERO DE MATERIAS REPOBRADAS (NMR)
11. PROBABILIDADES Y CASOS INTERESANTES
- CASO I
- CASO II

El archivo CODIGOS.html fue generado desde un documento R Markdown (.Rmd) utilizando RStudio.

Para reproducirlo se puede de dos maneras:

Se puede abrir manualmente:
1. Doble clic → CODIGOS.html
2. Clic en el botón Code
3. Clic en Download ZIP
4. Extraer la carpeta
   
En RStudio:

1. File → Open File…
2. Seleccionar el archivo .Rmd del proyecto (Este archivo es el que generó tu HTML)

## Autores
- *Carol Valentina Castellanos Jaimes*
- *Jairo Jose Cordoba Musso*
- *Samuel David Medina Contreras*
- *Paula Andrea Prado Iglesias*

Asignatura de probabilidad y estadisticas. Facultad de ingenieria, Universidad del Magdalena.

## Licencia
Uso exclusivamente academico.
