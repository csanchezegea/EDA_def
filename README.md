![banner](https://github.com/csanchezegea/EDA_def/blob/Dani/imagenes/Purple%20Simple%20Happy%20Halloween%20Facebook%20Cover.png)
# OBJETIVOS
Este trabajo corresponde a un Analisis Exploratorio de datos de un Dataset sobre defunciones en Argentina.

# INTRODUCCION
La limpieza de datos es una etapa fundamental en cualquier proyecto de análisis de datos. Los datos que utilizamos pueden estar sujetos a errores, valores faltantes o ruido, lo que puede comprometer la calidad de nuestros resultados. En este trabajo, abordaremos la limpieza de un dataset de defunciones, utilizando diversas herramientas y técnicas proporcionadas en clases.

Para llevar a cabo este proceso, emplearemos las siguientes librerías de Python:
- pandas: Esta librería es esencial en la manipulación y limpieza de datos. Nos permite cargar y explorar el dataset de defunciones de 
  manera eficiente.
- numpy: Utilizaremos numpy para realizar operaciones numéricas y manejar valores nulos o atípicos en nuestros datos.
- matplotlib.pyplot y seaborn: Estas librerías nos proporcionarán las herramientas necesarias para la visualización de datos, lo que nos 
  ayudará a identificar patrones, tendencias y posibles problemas en nuestro conjunto de datos.
- scipy.stats: Será útil para llevar a cabo pruebas estadísticas que nos permitan identificar valores atípicos o distribuciones inusuales 
  en nuestros datos.
- sklearn.preprocessing.LabelEncoder: Esta librería nos facilitará la codificación de variables categóricas, un paso esencial en la 
  preparación de datos para su posterior análisis.

El objetivo de este trabajo es aplicar estas herramientas en el contexto de la limpieza de un dataset de defunciones. A lo largo del proceso, realizaremos tareas como la identificación y tratamiento de valores nulos, la detección y manejo de valores atípicos, la transformación de datos y la codificación de variables categóricas. Además, llevaremos a cabo un Análisis Exploratorio de Datos (EDA) para comprender mejor la naturaleza de nuestro conjunto de datos y extraer información relevante.

La limpieza de datos es un paso crucial en la preparación de datos para su posterior análisis. Al finalizar este trabajo, estaremos en una posición sólida para aplicar técnicas avanzadas de análisis y modelado a nuestros datos de defunciones, lo que nos permitirá obtener insights valiosos y tomar decisiones informadas.

# ANEXOS
Las características del dataset son:
- dataset: arg-def-mensual-15-21
- cantidad de casos totales entre los años 2015-2020: 2.516.784 defunciones
- variables disponibles: 11
- nombre de las variables:
- region: región
- jurisdiccion : jurisdicciones nacionales
- mes_anio_defunción: mes y año de defunción
- mes_def: mes de defunción
- anio_def : año de defunción
- sexo_id: sexo id
- sexo_nombre: descripción de la variable sexo al nacimiento.
- grupo_etario: grupos etarios
- grupo_causa_defuncion_CIE10: grupos de causas de defunción utilizadas en los anuarios de la DEIS. (Estadísticas vitales,Información 
  Básica,Argentina – Año 2020. Anexo 2: Lista de mortalidad según causas seleccionadas, Estadísticas vitales – Argentina Año 2020, pg 155)
- cod_causa_muerte_CIE10: código CIE10 a tres dígitos.
- cantidad : 1 ( representa la cantidad de defunciones para la fila determinada, al ser una base desagregada, siempre será igual a 1).
![exp graf](https://github.com/csanchezegea/EDA_def/blob/Dani/imagenes/imgs_graf.png)


