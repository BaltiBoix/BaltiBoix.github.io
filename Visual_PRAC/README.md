# M2.859 - Visualización de datos aula 2  
<h2>A9: Creación de la visualización y entrega del proyecto (Práctica)</h2>
<h3>Visualización data storytelling (PRAC)</h3>

1.	**Título y descripción de la visualización creada.**<br>
La perspectiva de género en los resultados del estudio PISA para España. ¿Por qué no destacan las mujeres en matemáticas?

2.	**Origen y licencia de los datos.**<br>
He decidido utilizar los datos del estudio PISA  2018.   Es un estudio de la OCDE sobre el nivel educativo de los estudiantes de 15 años.
Los datos se han descargado desde Pisa 2018 Database.
Student questionnaire data file  (489  MB) en formato SPSS (TM) Data Files (compressed).
PISA products license.

3.	**Herramienta con la cual se ha hecho. Características de esta herramienta.**<br>
Se ha utilizado R (RStudio) para procesar los datos del estudio. El cálculo de estadísticos no es trivial. Se han realizado con las rutinas en R propuestas en el blog Software Técnico Libre de Miguel Díaz Kusztrich. Las tablas relevantes para la visualización se han guardado en ficheros en formato CSV para su posterior uso.<br> 
La visualización se ha realizado con Tableau Public. Esta herramienta permite la importación de los datos desde ficheros CSV y la generación de gráficos interactivos en hojas de trabajo. Estas se integran en dashbords que a su vez se presentan en historias secuencialmente.<br>
Se ha programado con d3.js una gráfica interactiva(lollipop) para presentar los datos por Comunidad Autónoma.

4.	**Presentación de la navegación / animación de la visualización creada.**<br>
Tableau:<br>
>> <a href="https://public.tableau.com/app/profile/baltasar.boix/viz/PISA_2_16383060898200/Historia1?publish=yes">La perspectiva de género en los resultados del estudio PISA para España</a><br>
 d3.js:<br>
>> <a href="https://baltiboix.github.io/Visual_PRAC/ccaa.html">Resultados PISA 2018 por Comunidad Autónoma</a>

5.	**Análisis de los elementos visuales usados: tipo de gráficos, interacción, colores, textos...**<br>
Se han utilizado los siguientes elementos visuales en Tableau:<br>
-	Gráficos de forma utilizando iconos (Iconos de Gráficos - Iconos gratuitos de 132,939 (flaticon.es)) de distinto tamaño para resaltar la diferencia en desempeño entre chicos y chicas.<br>
-	Gráficos de mapa (choropleth map) con los resultados por CCAA y selección interactiva de la materia a visualizar. Para mostrar la Islas Canarias al lado de la península se han superpuesto dos mapas.
-	Gráficos de barra de error para mostrar la diferencia de puntuaciones entre sexos por CCAA.<br>
-	Gráficos de círculos con los resultados según formación de la madre y propiedad del colegio (Público o Privado).<br>
-	Texto e imágenes.<br><br>
La navegación entre gráficos se realiza con puntos de historia con un texto explicativo.<br>
La paleta de colores utilizada ha sido Tableau Classic 10. Se ha comprobado la coherencia de colores entre gráficos.<br><br>
En d3.js se ha programado un script que dibuja lollipop horizontal con botones tipo radio y tooltips interactivos. 

6.	**Reflexiones finales sobre que explica y que aporta la visualización creada y qué formas de captar la atención del usuario se han utilizado.**<br>
La visualización describe el resultado de los tests PISA de los chicos y chicas de 15 años en España en el año 2018 e investiga la diferencia entre sexos geográficamente, según el tipo de escuela y la formación de la madre.<br>
Los resultados relativos de las chicas se reflejan posteriormente en una baja proporción de mujeres con estudios STEM (Science, Tecnology, Engineering and Mathematics).<br><br>
*“If we fail to understand that we are more alike from birth than we are different and treat our children accordingly, our world will continue to be gendered. Undoing these assumptions is not easy, but perhaps we can all think twice before we tell a little boy how brave he is and a little girl how kind or perfect she is.”*<br>
<a href="https://www.bbc.com/future/article/20210524-the-gender-biases-that-shape-our-brains">The gender biases that shape our brains - BBC Future</a>


<a href="https://www.bbc.com/news/education-31733742">Clever girls lack confidence in science and maths - BBC News</a><br>
<a href="https://www.bbc.com/news/education-30933493">'Girls outperform boys at school' despite inequality - BBC News</a><br>
<a href="https://www.bbc.com/future/article/20210524-the-gender-biases-that-shape-our-brains">The gender biases that shape our brains - BBC Future</a>
