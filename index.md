# Aprendizaje Estadístico 2025

Este es un curso introductorio al aprendizaje estadístico, con énfasis principalmente en los fundamentos matemáticos y estadísticos de los principales algoritmos de aprendizaje automático y reconocimiento de patrones. El tema central del curso es el estudio de métodos para obtener información útil a partir de datos. Abordamos temas principales como el aprendizaje supervisado y no supervisado, los modelos de regresión, y algunos tópicos recientes como el aprendizaje profundo. Al final del curso, los estudiantes comprederán los fundamentos de los algoritmos más populares del aprendizaje estadístico. Para aprovechar de mejor manera el curso, es recomendable que los estudiantes estén familiarizados con temas de álgebra lineal, cálculo, estadística matemática, y tener conocimientos de al menos un lenguaje de programación (*e.g.* Python, R, Matlab, C++, u otros).


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-sl2025.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Miércoles, de 19:50 a 21:25 horas, y viernes de 18:10 a 19:45.

### Office Hours
<div id='id-office'/>

* Por definir. Por solicitud del estudiante. También pueden enviar sus dudas por correo electrónico.


# Material del curso
<div id='id-material'/>

**No.**  | **Fecha**    | **Tópicos**                                                 | **Recursos**
-------- | ------------ | ----------------------------------------------------------- |  -------------------------------------
01       | 15.01.2025   | Introducción. Repaso de Probabilidad. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} |  
02       | 17.01.2025   | Variables aleatorias. Densidad y función de distribución. [Aula 02](aulas/Aula02.pdf){:target="_blank"} | [rvs.ipynb](code/rvs.ipynb){:target="_blank"}
03       | 22.01.2025   | Función de cuantiles. Contraste entre distribuciones. PP-plots, QQ-plots, KS. | [qqplots.ipynb](code/qqplots.ipynb){:target="_blank"} [fitting.ipynb](code/fitting.ipynb){:target="_blank"}
04       | 24.01.2025   | Estadísticos. Entropía, información mutua, Kullback-Leibler. [Aula 03](aulas/Aula03.pdf){:target="_blank"} | [data_exploration.ipynb](code/data_exploration.ipynb){:target="_blank"}
05       | 24.01.2025   | Funciones multivariadas. Normal multivariada. [Aula 04](aulas/Aula04.pdf){:target="_blank"} | [generate_gaussian.ipynb](code/generate_gaussian.ipynb){:target="_blank"}
06       | 29.01.2025   | Análisis de Componentes Principales. <br/> [Aula 05](aulas/Aula05.pdf){:target="_blank"} | [pca.ipynb](code/pca.ipynb) [deport.csv](code/deport.csv)
07       | 31.01.2025   | Interpretación del PCA. <br/> [Aula 06](aulas/Aula06.pdf){:target="_blank"} | 
L1       | 31.01.2025   | Lista 1. **Fecha de Entrega: 14 de febrero.** | [Lista 01](listas/lista01.pdf){:target="_blank"} [areas.csv](listas/areas.csv){:target="_blank"} 
08       | 05.02.2025   | Escalamiento Multidimensional. <br/>  [Aula 07](aulas/Aula07.pdf){:target="_blank"} | [md_scaling.ipynb](code/md_scaling.ipynb){:target="_blank"}
09       | 07.02.2025   | Distancia de Mahalanobis. Kernel PCA, Volume Ellipsoid Method. [Aula 08](aulas/Aula08.pdf){:target="_blank"} | [kernel-pca.ipynb](code/kernel-pca.ipynb){:target="_blank"} [kernel-pca2.ipynb](code/kernel-pca2.ipynb){:target="_blank"} 
10       | 12.02.2025   | Variables latentes: Análisis de Componentes Independientes (ICA). [Aula 09](aulas/Aula09.pdf){:target="_blank"} | [ica.ipynb](code/ica.ipynb){:target="_blank"} <br/> [horse.jpg](code/horse.jpg){:target="_blank"} [morro.jpg](code/morro.jpg){:target="_blank"} [plane.jpg](code/plane.jpg){:target="_blank"} [race.jpg](code/race.jpg){:target="_blank"}  
11       | 12.02.2025   | Factoración No-Negativa de Matrices (NNMF). Sistemas de Recomendación. [Aula 10](aulas/Aula10.pdf){:target="_blank"} | [movies.csv](code/movies.csv){:target="_blank"} [ratings.csv](code/ratings.csv){:target="_blank"} <br/> [recommender.ipynb](code/recommender.ipynb){:target="_blank"} 
L2       | 14.02.2025   | Lista 2. **Fecha de Entrega: 28 de febrero.** | [Lista 02](listas/lista02.pdf){:target="_blank"} [weather.csv](listas/weather.csv){:target="_blank"} [crimes.dat](listas/crimes.dat){:target="_blank"} 
12       | 19.02.2025   | *Manifold Learning I*: Isomap, SNE y t-SNE, UMAP. [Aula 11](aulas/Aula11.pdf){:target="_blank"} | 
13       | 21.02.2025   | *Manifold Learning II*: Spectral embedding, LLE, SOM. [Aula 12](aulas/Aula12.pdf){:target="_blank"} | 
14       | 26.02.2025   | Estimación de densidades por kernels (KDE). <br/> [Aula 13](aulas/Aula13.pdf){:target="_blank"} |
15       | 28.02.2025   | Agrupamiento jerárquico. <br/> [Aula 14](aulas/Aula14.pdf){:target="_blank"} | 
L3       | 05.03.2025   | Lista 3. **Fecha de Entrega: 21 de marzo.**   | [Lista 3](listas/lista03.pdf){:target="_blank"} [wines.csv](listas/wines.csv){:target="_blank"} [hpi-data-2016.xlsx](listas/hpi-data-2016.xlsx){:target="_blank"} [countries_binary.xlsx](listas/countries_binary.xlsx){:target="_blank"} 
16       | 07.03.2025   | K-means y variantes de K-means. <br/> [Aula 15](aulas/Aula15.pdf){:target="_blank"} |  
17       | 12.03.2025   | Métodos de agrupamiento basados en densidad: Means-Shift, DBSCAN, OPTICS, BIRCH. [Aula 16](aulas/Aula16.pdf){:target="_blank"} | 
18       | 14.03.2025   | Mezclas gaussianas. Algoritmo EM. <br/> [Aula 17](aulas/Aula17.pdf){:target="_blank"} | 
19       | 19.03.2025   | Agrupamiento espectral. Algoritmo de Shi-Malik. [Aula 18](aulas/Aula18.pdf){:target="_blank"} | 
20       | 21.03.2025   | Métricas para algoritmos de clustering. <br/> [Aula 19](aulas/Aula19.pdf){:target="_blank"} | [clustering-metrics.ipynb](code/clustering-metrics.ipynb){:target="_blank"} <br/> [silhouette.ipynb](code/silhouette.ipynb){:target="_blank"}
21       | 26.03.2025   | Modelación predictiva. <br/> [Aula 20](aulas/Aula20.pdf){:target="_blank"} | 
22       | 26.03.2025   | KNN. <br/> [Aula 21](aulas/Aula21.pdf){:target="_blank"} | 
23       | 02.04.2025   | El clasificador bayesiano óptimo. <br/> | 
24       | 09.04.2025   | Presentación de seminarios del Primer Proyecto. |  
25       | 23.04.2025   | Cálculo teóríco del clasificador bayesiano. <br/> | 
26       | 25.04.2025   | Optimalidad del clasificador bayesiano. Cotas de error. Ejemplos. <br/> | 
27       | 30.04.2025   | *Naïve Bayes*. Cálculo de la conjunta sin independencia. <br/> | 
28       | 02.05.2025   | Análisis Discriminante. <br/> | 
29       | 07.05.2025   | Árboles de Decisión. <br/> | 
30       | 09.05.2025   | Modelos de ensamblaje. *Random Forests*. <br/> | 
31       | 14.05.2025   | Modelos lineales I: regresión logística. <br/> | 
32       | 16.05.2025   | Modelos lineales II: Perceptrón. SVM. <br/> | 
33       | 21.05.2025   | Regresión lineal: OLS. Ecuaciones normales. <br/> | 
34       | 23.05.2025   | Regresión lineal: pruebas de hipótesis, gráficos de diagnóstico. | 
35       | 23.05.2025   | Ejemplos de regresión en Statsmodels. | 
36       | 04.06.2025   | Presentación de proyectos finales. | 


# Proyectos
<div id='id-prj1'/>

En el curso se elaborarán dos proyectos.

## Primer Proyecto (Ecobici)
<div id='id-proj1'/>

**No.**  | **Fecha**    | **Tópicos**                                                         
-------- | ------------ | ------------------------------------------------------------------- 
P1       | 07.03.2025   | [Proyecto 1](proyectos/Proyecto1.pdf){:target="_blank"} <br/> Coordenadas de estaciones [stations.json](proyectos/stations.json){:target="_blank"} [stations.csv](proyectos/stations.csv){:target="_blank"} 
.        | 09-11.04.2025   | Presentaciones 
.        | 11.04.2025   | Entrega del reporte, código y presentación 


## Segundo Proyecto (Tema Libre)
<div id='id-proj2'/>

**No.**  | **Fecha**    | **Tópicos**                                                         
-------- | ------------ | ------------------------------------------------------------------- 
P2       | 08.05.2025   | Indicaciones del proyecto 2. 
.        | 20.05.2025   | Fecha límite para elegir tema. 
.        | 02-06.06.2025   | Presentaciones 

## Horarios presentaciones Proyecto 2
<div id='id-hor2'/>

**Fecha**    | **Tópicos**                | **Tema**             
------------ | -------------------------- | --------------------  
04.06.2025   | Sebastián y Aarón          | 
04.06.2025   | Mario y Mariel             | 
04.06.2025   | Pablo, Ximena y Juan Pablo | 
04.06.2025   | Jorge y Allan              | 
04.06.2025   | Juan Luis y Nicolle        | 
04.06.2025   | Sharis y Montse            | 
06.06.2025   | Diana y Franco             | 
06.06.2025   | Joab y Paulo               | 
06.06.2025   | Manu y Sofi                | 
06.06.2025   | Juan Miguel y Pedro        | 
06.06.2025   | Gaby y Lou                 | 


# Referencias
<div id='id-ref'/>

### Textos:

* [R. Duda, P. Hart, D. Stork (2000). *Pattern classification*.](https://libgen.li/adsfdfdea9d8171ef45f0b2eea8030490d0YP80AFIV){:target="_blank"}

* [G. Strang (2019). *Linear Algebra and Learning from Data*.](http://library.lol/main/A556CCA72B3B8F9D8186E3685FFC8877){:target="_blank"}

### Referencias adicionales:

* [G. James, D. Witten, T. Hastie, R. Tibshirani (2023). *An Introduction to Statistical Learning with Applications in Python*.](https://libgen.li/ads2da57b70be7a957abb9f7364ccbced40KR0PD925){:target="_blank"}

* [C. Bishop (2000). *Pattern Recognition and Machine Learning*.](https://libgen.li/adsae9f928d7d04112f9e8857bcd100e59dIO5FYYXZ){:target="_blank"}

* [T. Hastie, R. Tibshirani, J. Friedman (2013). *The Elements of Statistical Learning*.](https://libgen.li/adsa3b44a071c37f15474df44c4a0c67976CAHTWUVR){:target="_blank"}

* [K. Murphy (2012). *Machine Learning: a Probabilistic Perspective*.](https://libgen.li/ads8ecfeeb2e1f9a19c770fba1ff85fa5662544SKWB){:target="_blank"}

* [K.-L. Chung (2000). *A Course in Probability Theory*](https://libgen.li/ads1ec33c81975e516dd15b89f3b371a68fX3EH7EX2){:target="_blank"}

* [M. Lefebvre (2011). *Basic Probability with Applications*](https://libgen.li/adsf3b9314ca31e0289d5fcd6eeda01308aVRY6WN2J){:target="_blank"}

* [A. Izenman (2008). *Modern Multivariate Statistical Techniques: Regression, Classification and Manifold Learning*.](https://libgen.li/adsa23c9e5ed1112db6b7951a15001e5b68QX9128G0){:target="_blank"}

* [K. Fukunaga (1990). *Introduction to Statistical Pattern Recognition*.](https://libgen.li/adsf9b5b4f49d36184c6cf3bf36375f49beO7JPNGMQ){:target="_blank"}

* [C. Giraud (2021). *Introduction to High-Dimensional Statistics*.](https://libgen.li/ads73524b8ea60d921f8e5a909d492a1e5fTNAWKHJ2){:target="_blank"}

### Referencias avanzadas:

* [L. Devroye, L. Györfi, G. Lugosi (1996). *A Probabilistic Theory of Pattern Recognition*.](https://libgen.li/ads60f75d016a9c96d67d752536b9d1753aKJKZR9XI){:target="_blank"}

* [S. Shalev-Shwartz, S. Ben-David (2014). *Understanding Machine Learning: From Theory to Algorithms*.](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf){:target="_blank"}

* [P. Rigollet (2015). *Mathematics for Machine Learning*.](https://ocw.mit.edu/courses/mathematics/18-657-mathematics-of-machine-learning-fall-2015/lecture-notes/MIT18_657F15_LecNote.pdf){:target="_blank"}

---
