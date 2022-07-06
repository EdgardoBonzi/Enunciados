# Enunciados
## A. Curso de Python   
A partir de la 2da semana de Agosto dictaremos el **Curso de Introducción a la programación en Python**.  
A partir de la 1ra semana de Octubre dictaremos el **Curso de Python Científico**.  
En el siguiente link encontrarás la información de los Cursos y el link para inscribirte.  
https://github.com/EdgardoBonzi/AnuncioPython.git

## B. Física basada en Machine Learning y cálculos *ab initio*

Profesores:
Gabriela GRAD gabriela.grad@unc.edu.ar  
Edgardo BONZI edgardo.bonzi@unc.edu.ar

En el Laboratorio de Espectrometría de Radiaciones, realizamos diferentes lineas de investigación que incluye desde mediciones de espectros de radiación, cálculos por el Método Monte Carlo, estudios teoricos de diversos materiales tales como óxidos, aleaciones, etc, mediante la Teoría del Funcional Densidad (DFT), en donde tambien aplicamos **técnicas de Machine Learning en la física**.

Aquí dejamos las **propuestas de Trabajos Finales**

### 1. Algoritmo Genético para búsqueda de nanocluster de sistemas atómicos

Los clusters, como agregados de unos pocos a miles de átomos o moléculas, unen el mundo microscópico de átomos y moléculas con el mundo macroscópico de los materiales.  Las simulaciones por Algoritmo Genético (GA) permiten generar un conjunto de configuraciones representativas de estos sistemas de los cuales se puede extraer propiedades estructurales y termodinámicas. 

Las propiedades físicas y químicas de un cluster están determinadas por la estructura de su estado fundamental, las cuales son significativamente diferentes a las de los sistemas masivos y dependen sensiblemente del tamaño del grupo, por su relación superficie-volumen. 
Determinar la estructura del estado fundamental de un cúmulo es una tarea desafiante debido a la extrema complejidad de la Energía Potencial Superficial (PES) de alta dimensión.  La minimización energética es un método costoso para explorar un gran número de estructuras de nanocluster. 

La dinámica molecular (MD) permite relajar el sistema en función del tiempo y la temperatura, al simular la dinámica del mismo mediante la integración de las ecuaciones de movimiento de Newton para cada átomo. Considerando que la MD relaciona los efectos mecánico cuánticos de los electrones, incluídos en el cálculo de la energía y las fuerzas, con el movimiento clásico de los núcleos .

El GA es un método de optimización global eficiente para explorar el PES de los clústers, con cálculos mecánico cuanticos por el método ab initio. La propuesta es desarrollar un programa de GA en Python y sus librerias, para determinar las estructuras de energía más baja de una variedad de grupos elementales y compuestos (C, BN, Au, Ag), e investigar sus propiedades físicas las cuales serán comparadas con datos experimentales de nanomateriales. 

Esta propuesta de Trabajo Final para la Licenciatura en Física, conlleva una continuación en una Tesis Doctoral que incluya machine learning en física y posibilidad de realizar un posdoctorado en la Universidad Humboldt de Berlín Alemania.

### 2. Clustering de Cluster mediante Machine Learning

Los clusters, como agregados de unos pocos a miles de átomos o moléculas, unen el mundo microscópico de átomos y moléculas con el mundo macroscópico de los materiales.  

Generando cluster y relajando su energía nos permite obtener conjuntos de configuraciones representativas de estos sistemas, de los cuales se puede extraer propiedades estructurales y termodinámicas. 

Las propiedades físicas y químicas de un cluster están determinadas por la estructura de su estado fundamental, las cuales son significativamente diferentes a las de los sistemas masivos y dependen sensiblemente del tamaño del grupo, por su relación superficie-volumen. 
Determinar la estructura del estado fundamental de un cúmulo es una tarea desafiante debido a la extrema complejidad de la Energía Potencial Superficial (PES) de alta dimensión.  La minimización energética es un método costoso para explorar un gran número de estructuras de nanocluster. 

La dinámica molecular (MD) permite relajar el sistema en función del tiempo y la temperatura, al simular la dinámica del mismo mediante la integración de las ecuaciones de movimiento de Newton para cada átomo. Considerando que la MD relaciona los efectos mecánico cuánticos de los electrones, incluídos en el cálculo de la energía y las fuerzas, con el movimiento clásico de los núcleos .

El Clustering o análisis de conglomerados es una técnica de aprendizaje automático, que agrupa en diferentes grupos al conjunto de objetos en estudio,  según tengan características similares, via un método de análisis del Machine Learning (ML) de aprendizaje no supervisado.  Ello nos permitirá explorar la característica de los cluster que origine una menor PES.

La propuesta es desarrollar un programa de ML en Python y sus librerias, para determinar las características de las estructuras de cluster con energía más baja, de una variedad de grupos elementales y compuestos (C, BN, Au, Ag), e investigar sus propiedades físicas. 

Esta propuesta de Trabajo Final para la Licenciatura en Física, conlleva una continuación en una Tesis Doctoral que incluya machine learning en física y posibilidad de realizar un posdoctorado en la Universidad Humboldt de Berlín Alemania.

### 3. Propuesta de cálculos en superficies y nanomateriales
Estudios teóricos basados en la DFT han sido, en las últimas dos décadas, de gran importancia tanto aplicados a la física de materiales como a comprender los fundamentos de las reacciones químicas, estudio de superficies y mecanismos de catálisis utilizados en la industria quimica en los cuales se aumenta la velocidad de una reacción quimica.
Es interesante el estudio de la difusión de metales en materiales low dimension, es posible estudiar la localización del atomo de metal, de acuerdo a la interaccion, a la transferencia de carga, a la energía de adsorción en los posibles sitios a depositarse. La barrera de potencial se puede estudiar con el método del Nudget Elastic Band NEB que forma parte del QE.
Una propuesta es realizar cálculos de adsorción de átomos metalicos en superfices de cristales, por ejemplo (001), (110) y (111) o materials low dimension. El objetivo es estudiar los procesos involucrados que son de interés en diferentes áreas de la física como por ejemplo la adsorción como proceso alternativo para la remoción de contaminantes que puedan tener impacto en el ambiente.
Otra propuesta es realizar cálculos en grafeno, o en otros nanomateriales, con una vacancia, con el objetivo de estudiar la estructura electrónica. Se pueden realizar cálculos de densidad de estados y densidad de carga para analizar la influencia de la vacancia en la estructura electrónica. Este estudio es extensible a otros materiales bidimensionales con estructura hexagonal.

### 4. Propuesta de cálculos de materiales dopados
Para realizar cálculos en sistemas sólidos utilizamos la teoría de la funcional densidad con el método all electron FP-LAPW implementado en el código Wien2k. Una de nuestras líneas de trabajo es el estudio de óxidos dopados con átomos de la serie 3d de metales de transición. Analizamos la relajación y como se modifican las posiciones atómicas y la estructura electrónica de estos sistemas. Producido el efecto Jahn Teller en alguno de los sistemas analizados, el objetivo es estudiar la interacción entre el momento magnético y el campo cristalino. También nos interesa analizar las funciones de Wannier que venimos aplicando en otros sistemas sólidos y estudiando la información que obtenemos del Hamiltoniano.

### 5. Obtención de parámetros de resonancia magnética nuclear (RMN) mediante cálculos de funcional densidad (DFT)
La resonancia magnética nuclear (RMN) es una técnica experimental ampliamente usada para proveer información indirecta de la estructura local alrededor de núcleos seleccionados, tanto en estado líquido (moléculas aisladas) como en sólidos (estructura periódica). La RMN detecta la respuesta del núcleo a un campo externo relacionado con la reorientación del momento magnético nuclear. Esta propuesta apunta a realizar cálculos de DFT orientados a obtener parámetros y espectros de RMN con el fin de estudiarlos y comparárlos con resultados experimentales.
Contamos con programas de cálculos de primeros principios que deseamos poner a punto para predecir el corrimiento químico de distintos núcleos y el apantallamiento, tanto para moléculas aisladas como para sólidos, y compararlos con los correspondientes espectros de RMN. En este proceso, comenzaremos con moléculas a fin de establecer la metodología a usar, para luego extender este procedimiento a compuestos de interés farmacéutico.

### 6. Propuesta para los interesados en el medio ambiente
La propuesta es realizar la Determinación de contendos de Cesio y Plomo en sedimentos lacustres, mediante especroscopía gamma y redes neuronales. Con las mismas, se propone hacer dataciones en diversos lagos, comenzando por el Lago San Roque, Mar Chiquita, Lago Puán y del Monte, revisando y mejorando modelos de evolución de estos materiales en los lagos. Este trabajo es en colaboración con investigadores del Centro de Investigaciones en Ciencias de la Tierra [CICTERRA] y el Laboratorio de Radioisótopos del Departamento F. Forel de la Universidad de Ginebra.



### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
