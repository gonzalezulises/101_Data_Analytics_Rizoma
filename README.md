## Repositorio de curso sobre Data Analytics

Business Analytics (BA) consiste en explorar y analizar grandes cantidades de datos para obtener información sobre el desempeño empresarial pasado con el fin de guiar la planificación empresarial futura. Este curso presenta un conjunto de métodos avanzados centrados en datos que cubren las tres direcciones principales de BA: descriptivo (“¿qué pasó?”), predictivo (“¿qué pasará?”) y prescriptivo (“¿qué debería pasar?”). Los métodos se aplicarán a varios casos de negocios con el objetivo de demostrar cómo extraer valor comercial de los datos, brindar soporte para la toma de decisiones basada en datos junto con principios efectivos de gestión de datos.
Materiales de soporte para la formación en Data Analytics

**Instructor:** Ulises Gonzalez ([Rizoma](http://www.rizo.ma/), [Linkedin](https://www.linkedin.com/in/ulisesgonzalez/)

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/justmarkham/DAT8)

Tuesday | Thursday
--- | ---
8/18: [Introduction to Data Science](#class-1-introduction-to-data-science) | 8/20: [Command Line, Version Control](#class-2-command-line-and-version-control)
8/25: [Data Reading and Cleaning](#class-3-data-reading-and-cleaning) | 8/27: [Exploratory Data Analysis](#class-4-exploratory-data-analysis)
9/1: [Visualization](#class-5-visualization) | 9/3: [Machine Learning](#class-6-machine-learning)
9/8: [Getting Data](#class-7-getting-data) | 9/10: [K-Nearest Neighbors](#class-8-k-nearest-neighbors)
9/15: [Basic Model Evaluation](#class-9-basic-model-evaluation) | 9/17: [Linear Regression](#class-10-linear-regression)
9/22: [First Project Presentation](#class-11-first-project-presentation) | 9/24: [Logistic Regression](#class-12-logistic-regression)
9/29: [Advanced Model Evaluation](#class-13-advanced-model-evaluation) | 10/1: [Naive Bayes and Text Data](#class-14-naive-bayes-and-text-data)
10/6: [Natural Language Processing](#class-15-natural-language-processing) | 10/8: [Kaggle Competition](#class-16-kaggle-competition)
10/13: [Decision Trees](#class-17-decision-trees) | 10/15: [Ensembling](#class-18-ensembling)
10/20: [Advanced scikit-learn, Clustering](#class-19-advanced-scikit-learn-and-clustering) | 10/22: [Regularization, Regex](#class-20-regularization-and-regular-expressions)
10/27: [Course Review](#class-21-course-review-and-final-project-presentation) | 10/29: [Final Project Presentation](#class-22-final-project-presentation)

<!-
### Antes de que comience el curso
* Instalar [git] (http://git-scm.com/downloads).
* Cree una cuenta en el sitio web [Github] (https://github.com/).
* No es necesario descargar "GitHub para Windows" o "Github para Mac"
* Instale la [Distribución Anaconda] (http://continuum.io/downloads) de Python 2.7x.
* Si elige no usar Anaconda, aquí hay una lista de los [paquetes Python] (otros/python_packages.md) Deberá instalar durante el curso.
* Nos gustaría verificar la configuración de su computadora portátil antes de que comience el curso:
* Puede verificar su computadora portátil antes del taller intermedio de Python el martes 8/11 (5:30 pm-6:30pm), en el [15th & K Starbucks] (http://www.yelp.com/biz/starbucks-Washington-15) el sábado 8/15 (1 pm-3pm), o antes de la clase el martes 8/18 (5:30 pm-6:30pm).
* Alternativamente, puede caminar por la [lista de verificación de configuración] (otro/setup_checklist.md) usted mismo.
* Una vez que reciba una invitación por correo electrónico de Slack, únase a nuestro "equipo DAT8" y agregue su foto.
* Practique Python utilizando los recursos a continuación.
->

### Recursos de Python
* [Codecademy's Python course](http://www.codecademy.com/en/tracks/python): Buen material para principiantes, incluidos toneladas de ejercicios en el navegador.
* [Dataquest](https://www.dataquest.io): Utiliza ejercicios interactivos para enseñar a Python en el contexto de la ciencia de datos.
* [Google's Python Class](https://developers.google.com/edu/python/): Un poco más avanzado, incluidas horas de videos útiles de conferencias y ejercicios descargables (con soluciones).
* [Introduction to Python](http://introtopython.org/): Una serie de cuadernos de iPython que hacen un gran trabajo explicando conceptos y estructuras de datos de Core Python.
* [Python for Informatics](http://www.pythonlearn.com/book.php): Un libro muy orientado a principiante, con asociado [slides](https://drive.google.com/folderview?id=0B7X1ycQalUnyal9yeUx3VW81VDg&usp=sharing) and [videos](https://www.youtube.com/playlist?list=PLlRFEj9H3Oj4JXIwMwN1_ss1Tk8wZShEJ).
* [A Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182): Lea la sección de descripción general para una introducción muy rápida a Python.
* [Python 2.7 Quick Reference](https://github.com/justmarkham/python-reference/blob/master/reference.py):Mi guía orientada a principiantes que demuestra conceptos de pitón a través de un ejemplo corto y bien commentados.
* [Beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) Código de taller: útil para revisión y referencia.
* [Python Tutor](http://pythontutor.com/): Le permite visualizar la ejecución del código Python.

<!--
### Formularios de presentación
* [Formulario de comentarios](http://bit.ly/dat8feedback)
* [Tarea y presentaciones de proyectos](http://bit.ly/dat8homework)
-->

### [Proyecto del curso](project/README.md)

### [Comparación de modelos de aprendizaje automático](other/model_comparison.md)

### [Comparación de procedimientos y métricas de evaluación del modelo](other/model_evaluation_comparison.md)

### [Consejo para mejorar en la ciencia de datos](other/advice.md)

### [Recursos adicionales](#additional-resources-1)

-----

### Class 1: Introducción al Business Analytics
* Bienvenida a la formación
* Resumen del curso([slides](slides/01_course_overview.pdf))
* Introducción al Business Analytics ([slides](slides/01_intro_to_data_science.pdf))
* Discuta el proyecto del curso: [requirements](project/README.md) and [example projects](https://github.com/justmarkham/DAT-project-examples)
* Tipos de datos([slides](slides/01_types_of_data.pdf)) and [public data sources](project/public_data.md)

**Asignación:**
* Work through GA's friendly [command line tutorial](http://generalassembly.github.io/prework/command-line/#/) using Terminal (Linux/Mac) or Git Bash (Windows).
* Read through this [command line reference](code/02_command_line.md), and complete the pre-class exercise at the bottom. (There's nothing you need to submit once you're done.)
* Watch videos 1 through 8 (21 minutes) of [Introduction to Git and GitHub](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD), or read sections 1.1 through 2.2 of [Pro Git](http://git-scm.com/book/en/v2).
* If your laptop has any setup issues, please work with us to resolve them by Thursday. If your laptop has not yet been checked, you should come early on Thursday, or just walk through the [setup checklist](other/setup_checklist.md) yourself (and let us know you have done so).

**Recursos:**
*Para una mirada útil a los diferentes tipos de científicos de datos, lea [analizar los analizadores] (http://cdn.oreillystatic.com/oreilly/radarreport/0636920029014/analyzing_the_analyzers.pdf) (32 páginas).
* Para algunas ideas sobre lo que es ser un científico de datos, lea estas publicaciones breves de [Win-vector] (http://www.win-vector.com/blog/2012/09/on-being-a-data-Scientist/) y [DataScope Analytics] (http://datascopeopealytics.com/what-we-think/2014/07/31/six-qualities-of-a-great-data-scientist).
* Quora tiene una [FAQ de tema de ciencias de datos] (https://www.quora.com/data-science) con muchas preguntas y respuestas interesantes.
* Manténgase al día con los eventos locales relacionados con los datos a través del Data Community DC [Calendario de eventos] (http://www.datacommunitydc.org/calendar) o [boletín semanal] (http://www.datacommunitydc.org/newletter).
-----

### Clase 2: Línea de comandos y control de versiones
* Slack Tour
* Revise el ejercicio previo a la clase de la línea de comando ([code](code/02_command_line.md))
* Git and GitHub ([slides](slides/02_git_github.pdf))
* Línea de comando intermedia

**Tarea:**
* Completar la [command line homework assignment](homework/02_command_line_chipotle.md) con los datos de Chipotle.
* Revise el código del [beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) Talleres de Python.Si no se siente cómodo con ninguno de los contenidos (excluyendo las secciones de "solicitudes" y "API"), debe pasar algún tiempo este fin de semana practicando Python:
    * [Introduction to Python](http://introtopython.org/)hace un gran trabajo explicando Python Essentials e incluye toneladas de código de ejemplo.
    * Si te gusta aprender de un libro, [Python for Informatics](http://www.pythonlearn.com/html-270/) Tiene capítulos útiles sobre cadenas, listas y diccionarios.
    * Si prefiere ejercicios interactivos, pruebe estas lecciones de [Codecademy](http://www.codecademy.com/en/tracks/python): "Python listas y diccionarios" y "un día en el supermercado".
    *Si tiene más tiempo, pruebe las misiones 2 y 3 de [DataQuest's Learning Python](https://www.dataquest.io/course/learning-python) curso.
    *Si ya ha dominado estos temas y quiere más desafío, intente resolver [Python Challenge](http://www.pythonchallenge.com/) nNúmero 1 (decodificando un mensaje) y envíeme su código en Slack.
* Para darle un marco para pensar en su proyecto, mire [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk) (10 minutes). (Este es el [IPython notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/01_machine_learning_intro.ipynb) shown en el video.) Alternativamente, lea [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/), que se centra en un modelo de aprendizaje automático específico llamado árboles de decisión.
* **Opcional:** Navegar por un poco más [example student projects](https://github.com/justmarkham/DAT-project-examples), ¡Lo que puede ayudar a inspirar su propio proyecto!

**Recursos Git y Markdown:**
* [Pro Git](http://git-scm.com/book/en/v2) esUnExcelenteLibroParaAprenderGitLeaLosDosPrimerosCapítulosParaObtenerUnaComprensiónMásProfundaDelControlDeVersionesYElComandoBásicos.
* siQuieresPracticarMuchoGit (yAprenderMuchosMásComandos), [Git Immersion](http://gitimmersion.com/) parecePrometedor
* siQuieresEntenderCómoContribuirEnGitHub,PrimeroTienesQueEntender [forks and pull requests](http://www.dataschool.io/simple-guide-to-forks-in-github-and-git/).
* [GitRef](http://gitref.org/)esMiGuíaDeReferenciaFavoritaParaLosComandosGit,Y [Git quick reference for beginners](http://www.dataschool.io/git-quick-reference-for-beginners/) isUnaGuíaMásCortaConComandosAgrupadosPorFlujoDeTrabajo
* [Cracking the Code to GitHub's Growth](https://growthhackers.com/growth-studies/github) explicaPorQuéGithubEsTanPopularEntreLosDesarrolladores
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) proporcionaUnConjuntoExhaustivoDeEjemplosDeMarkdownConExplicacionesConcisasGithub's[Mastering Markdown](https://guides.github.com/features/mastering-markdown/)esUnaGuíaMásSimpleYAtractiva,PeroEsMenosIntegral

**Recursos de línea de comandos:**
* Si quieres profundizar mucho en la línea de comando, [Data Science at the Command Line](http://shop.oreilly.com/product/0636920032823.do) es un gran libro.El [companion website](http://datascienceatthecommandline.com/) Proporciona instrucciones de instalación para una "caja de herramientas de ciencia de datos" (una máquina virtual con muchas más herramientas de línea de comandos), así como una larga guía de referencia para las herramientas de línea de comandos populares.
* Si desea hacer más en la línea de comando con archivos CSV, pruebe [csvkit](http://csvkit.readthedocs.org/), que se puede instalar a través de `pip`.

-----

### Clase 3: Lectura y limpieza de datos
* Git y Github Surtido consejos([slides](slides/02_git_github.pdf))
* Revisar la tarea de la línea de comando ([solution](homework/02_command_line_chipotle.md))
* Pitón:
* Interfaz Spyder
* Ejercicio de bucle
* Lección de lectura de archivos con datos de seguridad de la aerolínea ([code](code/03_file_reading.py), [data](data/airlines.csv), [article](http://fivethirtyeight.com/features/should-travelers-avoid-flying-airlines-that-have-had-crashes-in-the-past/))
    *Ejercicio de limpieza de datos
    * Tutorial de la tarea de Python con datos de chipotle ([code](code/03_python_homework_chipotle.py), [data](data/chipotle.tsv), [article](http://www.nytimes.com/interactive/2015/02/17/upshot/what-do-people-actually-order-at-chipotle.html))

**Tarea:**
* Completar la [Python homework assignment](code/03_python_homework_chipotle.py) Con los datos de Chipotle, agregue un script de Python comentado a su repositorio de GitHub y envíe un enlace utilizando el formulario de envío de tareas.Tienes hasta el martes (9/1) para completar esta tarea. (**Nota: ** Los pandas, que se cubren en la clase 4, no deben usarse para esta tarea).

**Resources:**
* [Want to understand Python's comprehensions? Think in Excel or SQL](http://blog.lerner.co.il/want-to-understand-pythons-comprehensions-think-like-an-accountant/) Puede ser útil si todavía está confundido por las comprensiones de la lista.
* [My code isn't working](http://www.tecoed.co.uk/uploads/1/4/2/4/14249012/624506_orig.png) es un gran diagrama de flujo que explica cómo depurar los errores de Python.
* [PEP 8](https://www.python.org/dev/peps/pep-0008/) es la guía de estilo "clásica" de Python, y vale la pena leer si desea escribir un código legible que sea consistente con el resto de la comunidad de Python.
* Si quieres entender a Python en un nivel más profundo, Ned Batchelder's [Loop Like A Native](http://nedbatchelder.com/text/iter.html)y [Python Names and Values](http://nedbatchelder.com/text/names1.html)son excelentes presentaciones.

-----

### Clase 4: Análisis de datos exploratorios
* Pandas ([code](code/04_pandas.py)):
    * MOVIELENS 100K Clasificaciones de películas ([data](data/u.user), [data dictionary](http://files.grouplens.org/datasets/movielens/ml-100k-README.txt), [website](http://grouplens.org/datasets/movielens/))
    * Consumo de alcohol por país ([data](data/drinks.csv), [article](http://fivethirtyeight.com/datalab/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/))
    * Informes de avistamientos de ovnis([data](data/ufo.csv), [website](http://www.nuforc.org/webreports.html))
* Ejercicio de preguntas del proyecto

**Tarea:**
* La fecha límite para discutir las ideas de su proyecto con un instructor es el martes (9/1), y la redacción de la pregunta de su proyecto se vence el juevesy (9/3).
* Leer[How Software in Half of NYC Cabs Generates $5.2 Million a Year in Extra Tips](http://iquantny.tumblr.com/post/107245431809/how-software-in-half-of-nyc-cabs-generates-5-2) Para un excelente ejemplo de análisis de datos exploratorios.
* Leer [Anscombe's Quartet, and Why Summary Statistics Don't Tell the Whole Story](http://data.heapanalytics.com/anscombes-quartet-and-why-summary-statistics-dont-tell-the-whole-story/) Para un ejemplo clásico de por qué la visualización es útil.

**Recursos:**
* Browsing or searching the Pandas [API Reference](http://pandas.pydata.org/pandas-docs/stable/api.html) es una excelente manera de localizar una función incluso si no sabe su nombre exacto.
* [What I do when I get a new data set as told through tweets](http://simplystatistics.org/2014/06/13/what-i-do-when-i-get-a-new-data-set-as-told-through-tweets/) es una mirada divertida (pero esclarecedora) al proceso de análisis de datos exploratorios.

-----

### Clase 5: Visualización
* Tarea de Python con los datos de Chipotle adeudados ([solution](code/03_python_homework_chipotle.py), [detailed explanation](notebooks/03_python_homework_chipotle_explained.ipynb))
* Parte 2 del análisis de datos exploratorios con pandas([code](code/04_pandas.py))
* Visualización con pandas y matplotlib ([notebook](notebooks/05_pandas_visualization.ipynb))

**Tarea:**
* El informe de su pregunta de su proyecto se debe el jueves.
* Completar la [Pandas homework assignment](code/05_pandas_homework_imdb.py) con el [IMDb data](data/imdb_1000.csv). Tiene hasta el martes (9/8) para completar esta tarea.
* IfNo estás usando Anaconda, instale el[Jupyter Notebook](http://jupyter.readthedocs.org/en/latest/install.html)(anteriormente conocido como el cuaderno de ipython) utilizando`pip`. (El cuaderno Jupyter o Ipython se incluye con Anaconda).

**Recursos de pandas:**
* Para obtener más pandas, lea esto [three-part tutorial](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/), O revise estos dos cuadernos excelentes (pero extremadamente largos) en Pandas: [introduction](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_5-Introduction-to-Pandas.ipynb) and [data wrangling](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_6-Data-Wrangling-with-Pandas.ipynb).
* Si quieres profundizar en los pandas (y numpy), lee el libro [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do),Escrito por el Creador de Pandas.
* Este cuaderno demuestra los diferentes tipos de[joins in Pandas](notebooks/05_pandas_merge.ipynb), para cuando necesite descubrir cómo fusionar dos marcos de datos.
* Este es un buen tutorial breve sobre [pivot tables](https://beta.oreilly.com/learning/pivot-tables) en pandas.
* Para trabajar con datos geoespaciales en Python, [GeoPandas](http://geopandas.org/index.html) parece prometedor.Este [tutorial](http://michelleful.github.io/code-blog/2015/04/24/sgmap/) Utiliza Geopandas (y Scikit-Learn) para construir un "mapa callejero lingüístico" de Singapur.

**Recursos de visualización:**
* Mirar [Look at Your Data](https://www.youtube.com/watch?v=coNDCIMH8bk) (18 minutos) Para un excelente ejemplo de por qué la visualización es útil para comprender sus datos.
* Fo más sobre los pandas tramando, lea esto [notebook](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_7-Plotting-with-Pandas.ipynb) o el [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) De la documentación oficial de Pandas.
* Para aprender a personalizar aún más sus parcelas, navegue por este [notebook on matplotlib](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_4-Matplotlib.ipynb) o esto[similar notebook](https://github.com/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb).
* Leer [Overview of Python Visualization Tools](http://pbpython.com/visualization-tools-1.html) Para una comparación útil de matplotlib, pandas, seaborn, ggplot, bokeh, pygal y tramly.
* Para explorar diferentes tipos de visualizaciones y cuándo usarlas, [Choosing a Good Chart](http://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf) y[The Graphic Continuum](http://www.coolinfographics.com/storage/post-images/The-Graphic-Continuum-POSTER.jpg) son buenas referencias de una página y el interactivo [R Graph Catalog](http://shiny.stat.ubc.ca/r-graph-catalog/) tiene prácticas capacidades de filtrado.
* Esta [PowerPoint presentation](http://www2.research.att.com/~volinsky/DataMining/Columbia2011/Slides/Topic2-EDAViz.ppt) De la clase de minería de datos de Columbia contiene muchos buenos consejos para usar adecuadamente los diferentes tipos de visualizaciones.
* [Harvard's Data Science course](http://cs109.github.io/2014/) Incluye una excelente conferencia sobre[Visualization Goals, Data Types, and Statistical Graphs](http://cm.dce.harvard.edu/2015/01/14328/L03/screen_H264LargeTalkingHead-16x9.shtml) (83 minutos), para el cual el [slides](https://docs.google.com/file/d/0B7IVstmtIvlHLTdTbXdEVENoRzQ/edit) también están disponibles.

-----

### Clase 6: Aprendizaje automático
* Parte 2 de la visualización con pandas y matplotlib([notebook](notebooks/05_pandas_visualization.ipynb))
*Breve introducción al cuaderno Jupyter/Ipython
*Ejercicio de "aprendizaje humano":
    * [Iris dataset](http://archive.ics.uci.edu/ml/datasets/Iris) Organizado por el repositorio de aprendizaje automático de UCI
    * [Iris photo](http://sebastianraschka.com/Images/2014_python_lda/iris_petal_sepal.png)
    * [Notebook](notebooks/06_human_learning_iris.ipynb)
* Introducción al aprendizaje automático ([slides](slides/06_machine_learning.pdf))

**Tarea:**
*** Opcional: ** Complete el ejercicio de bonificación en la lista de [human learning notebook](notebooks/06_human_learning_iris.ipynb). ¡Tomará el lugar de cualquier tarea que pierda, pasado o futuro!Esto se debe el martes (9/8).
* Si no está usando Anaconda, instale [requests](http://www.python-requests.org/en/latest/user/install/)y[Beautiful Soup 4](http://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup)usando`pip`. (Ambos paquetes están incluidos con Anaconda).

**Recursos de aprendizaje automático:**
* Para un resumen muy rápido de los puntos clave sobre el aprendizaje automático, mire[What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk) (10 minutos) o leer el [associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/01_machine_learning_intro.ipynb).
* Para una introducción más profunda al aprendizaje automático, lea la Sección 2.1 (14 páginas) del excelente libro de Hastie y Tibshirani, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (¡Es una descarga gratuita de PDF!)
*La [Learning Paradigms](http://work.caltech.edu/library/014.html) Video (13 minutos) de [Caltech's Learning From Data course](http://work.caltech.edu/telecourse.html) Proporciona una buena comparación del aprendizaje supervisado versus no supervisado, así como una introducción al "aprendizaje de refuerzo".
* [Real-World Active Learning](https://beta.oreilly.com/ideas/real-world-active-learning) es una introducción legible y exhaustiva al "aprendizaje activo", una variación del aprendizaje automático en la que los humanos etiquetan solo las observaciones más "importantes".
* Para obtener una vista previa de parte del contenido de aprendizaje automático que cubriremos durante el curso, lea Sebastian Raschka's [overview of the supervised learning process](https://github.com/rasbt/pattern_classification/blob/master/machine_learning/supervised_intro/introduction_to_supervised_machine_learning.md).
* [Data Science, Machine Learning, and Statistics: What is in a Name?](http://www.win-vector.com/blog/2013/04/data-science-machine-learning-and-statistics-what-is-in-a-name/) Discute las diferencias entre estos (y otros) términos.
* [The Emoji Translation Project](https://www.kickstarter.com/projects/fred/the-emoji-translation-project)es una aplicación realmente divertida del aprendizaje automático.
* Busque el[characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/), y luego lee sobre el [67 distinct segments](http://doc.arcgis.com/en/esri-demographics/data/tapestry-segmentation.htm) en detalle.

**Recursos de cuaderno de iPython**
* Para un resumen de la introducción del cuaderno de iPython (y una vista previa de Scikit-Learn), mire [scikit-learn and the IPython Notebook](https://www.youtube.com/watch?v=IsXXlYVBt1M) (15 minutos) o leer el[associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/02_machine_learning_setup.ipynb).
*Si desea aprender el cuaderno de iPython, el oficial[Notebook tutorials](https://github.com/jupyter/notebook/blob/master/docs/source/examples/Notebook/Examples%20and%20Tutorials%20Index.ipynb) Son útiles.
*Esta [Reddit discussion](https://www.reddit.com/r/Python/comments/3be5z2/do_you_prefer_ipython_notebook_over_ipython/) Compara las fortalezas relativas del cuaderno de Ipython y Spyder.

-----

### Clase 7: Obtener datos
* Tarea de pandas con los datos de IMDB adeudados ([solution](code/05_pandas_homework_imdb.py))
* Ejercicio opcional de "aprendizaje humano" con los datos de iris adeudados ([solution](notebooks/06_human_learning_iris.ipynb))
* APIs ([code](code/07_api.py))
    * [OMDb API](http://www.omdbapi.com/)
* Web scraping ([code](code/07_web_scraping.py))
    * [IMDb: robots.txt](http://www.imdb.com/robots.txt)
    * [Example web page](data/example.html)
    * [IMDb: The Shawshank Redemption](http://www.imdb.com/title/tt0111161/)

**Tarea:**
*** Opcional: ** Complete el ejercicio de tarea enumerado en el [web scraping code](code/07_web_scraping.py). ¡Tomará el lugar de cualquier tarea que pierda, pasado o futuro!Esto se debe el martes (15/09).
* **Opcional: ** Si no estás usando Anaconda, [install Seaborn](http://stanford.edu/~mwaskom/software/seaborn/installing.html) usando `pip`. Si está utilizando Anaconda, instale SeaBorn corriendo `conda install seaborn`en la línea de comando.(Tenga en cuenta que algunos estudiantes en cursos pasados ​​han tenido problemas con Anaconda después de instalar Seorn).

**Recursos API**
*Este guión de Python para [query the U.S. Census API](https://github.com/laurakurup/census-api) fue creado por un ex alumno de DA.Es un poco más complicado que el ejemplo que usamos en la clase, está muy bien comentado y puede proporcionar un marco útil para escribir su propio código para consultar las API.
* [Mashape](https://www.mashape.com/explore) y [Apigee](https://apigee.com/providers)Permitirle explorar toneladas de diferentes API.Alternativamente, un [Python API wrapper](http://www.pythonforbeginners.com/api/list-of-python-apis) está disponible para muchas API populares.
* the [Data Science Toolkit](http://www.datasciencetoolkit.org/) es una colección de API basadas en la ubicación y relacionadas con el texto.
* [API Integration in Python](https://realpython.com/blog/python/api-integration-in-python/) Proporciona una introducción muy legible a las API REST.
* Microsoft's [Face Detection API](https://www.projectoxford.ai/demo/face#detection), que poderes[How-Old.net](http://how-old.net/), es un gran ejemplo de cómo se puede aprovechar una API de aprendizaje automático para producir una aplicación web convincente.

**Recursos de raspado web:**
* La[Beautiful Soup documentation](http://www.crummy.com/software/BeautifulSoup/bs4/doc/) es increíblemente minucioso, pero es difícil de usar como guía de referencia.Sin embargo, la sección en[specifying a parser](http://www.crummy.com/software/BeautifulSoup/bs4/doc/#specifying-the-parser-to-use) Puede ser útil si la hermosa sopa parece estar analizando una página incorrectamente.
* Para más hermosos ejemplos de sopa y tutoriales, ver [Web Scraping 101 with Python](http://www.gregreda.com/2013/03/03/web-scraping-101-with-python/), Un cuaderno de un ex alumno de DAT bien comentado en[scraping Craigslist](https://github.com/Alexjmsherman/DataScience_GeneralAssembly/blob/master/Final_Project/1.%20Final_Project_Data%20Scraping.ipynb), this [notebook](http://web.stanford.edu/~zlotnick/TextAsData/Web_Scraping_with_Beautiful_Soup.html) del texto de Stanford como curso de datos, y esto[notebook](https://github.com/cs109/2014/blob/master/lectures/2014_09_23-lecture/data_scraping_transcript.ipynb) y asociado [video](http://cm.dce.harvard.edu/2015/01/14328/L07/screen_H264LargeTalkingHead-16x9.shtml)del curso de ciencia de datos de Harvard.
* Para un tutorial de raspado web mucho más largo que cubre la hermosa sopa, LXML, XPath y Selenium, reloj[Web Scraping with Python](https://www.youtube.com/watch?v=p1iX0uxM1w8) (3 horas 23 minutos) de Pycon 2014. La [slides](https://docs.google.com/presentation/d/1uHM_esB13VuSf7O1ScGueisnrtu-6usGFD3fs4z5YCE/edit#slide=id.p) y [code](https://github.com/kjam/python-web-scraping-tutorial) también están disponibles.
* Para proyectos de raspado web más complejos, [Scrapy](http://scrapy.org/) es un marco de aplicaciones popular que funciona con Python.Tiene excelente [documentation](http://doc.scrapy.org/en/1.0/index.html), Y aquí hay un [tutorial](https://github.com/rdempsey/ddl-data-wrangling) con diapositivas y código detallados.
* [robotstxt.org](http://www.robotstxt.org/robotstxt.html) tiene una explicación concisa de cómo escribir (y leer) el `robots.txt` file.
* [import.io](https://import.io/) y [Kimono](https://www.kimonolabs.com/) afirmar que le permite raspar sitios web sin escribir ningún código.
* [How a Math Genius Hacked OkCupid to Find True Love](http://www.wired.com/2014/01/how-to-hack-okcupid/all/) and [How Netflix Reverse Engineered Hollywood](http://www.theatlantic.com/technology/archive/2014/01/how-netflix-reverse-engineered-hollywood/282679/?single_page=true) son dos ejemplos divertidos de cómo se ha utilizado el raspado web para crear conjuntos de datos interesantes.

-----

### Clase 8: vecinos K-nears
* Breve revisión de pandas ([cuaderno] (cuadernos/08_pandas_review.ipynb)))
* K-Near más vecinos y scikit-learn ([cuaderno] (cuadernos/08_knn_sklearn.ipynb))
* Ejercicio con los datos del jugador de la NBA ([cuaderno] (cuaderno/08_nba_knn.ipynb), [data] (https://github.com/justmarkham/dat4-students/blob/master/kerry/final/nba_players_2015.csv), [Dicción de datos] (https://github.com/justmarkham/dat-project-examples/blob/master/pdf/nba_paper.pdf)))
* Explorando la compensación de varianza de sesgo ([cuaderno] (cuadernos/08_bias_variance.ipynb))

**Tarea:**
* Asignación de lectura en la [compensación de varianza de sesgo] (tarea/09_bias_variance.md)
* Lea la [Introducción a la reproducibilidad] de Kevin (http://www.dataschool.io/reproducibilidad-is-not-just-for-researchers/), lea la guía de Jeff Leek para crear un análisis reproducible] (https: // github.com/jtleek/dataHaring), y vea este video relacionado [Video de Informe de Colbert] (http://thecolberstreport.cc.com/videos/dcyvro/austerity-s-sepersheet-error) (8 minutos).
* Trabaje en su proyecto ... ¡su primera presentación del proyecto está en menos de dos semanas!

**RECURSOS KNN**
* Para un resumen de los puntos clave sobre Knn y Scikit-Learn, mira [Getting started in scikit-learn with the famous iris dataset](https://www.youtube.com/watch?v=hd1W4CyPX58) (15 minutos) y [Training a machine learning model with scikit-learn](https://www.youtube.com/watch?v=RlQuVL6-qe8) (20 minutes).
* KNN soporta [distance metrics](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.DistanceMetric.html) aparte de la distancia euclidiana, como [Mahalanobis distance](http://stats.stackexchange.com/questions/62092/bottom-to-top-explanation-of-the-mahalanobis-distance), cual [takes the scale of the data into account](http://blogs.sas.com/content/iml/2012/02/15/what-is-mahalanobis-distance.html).
* [A Detailed Introduction to KNN](https://saravananthirumuruganathan.wordpress.com/2010/05/17/a-detailed-introduction-to-k-nearest-neighbor-knn-algorithm/) es un poco denso, pero proporciona una introducción más exhaustiva a KNN y sus aplicaciones.
* Esta conferencia en [Image Classification](http://cs231n.github.io/classification/) sCómo se podría utilizar cómo se podría usar KNN para detectar imágenes similares, y también toca temas que cubriremos en clases futuras (ajuste de hiperparámetro y validación cruzada).
* Algunas aplicaciones para las cuales KNN es muy adecuada son [object recognition](http://vlm1.uta.edu/~athitsos/nearest_neighbors/), [satellite image enhancement](http://land.umn.edu/documents/FS6.pdf), [document categorization](http://www.ceng.metu.edu.tr/~e120321/paper.pdf),y [gene expression analysis](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.208.993).

**Recursos Seaborn:**
* Para comenzar con Seaborn para la visualización, el sitio web oficial tiene una serie de [detailed tutorials](http://web.stanford.edu/~mwaskom/software/seaborn/tutorial.html) y un [example gallery](http://web.stanford.edu/~mwaskom/software/seaborn/examples/index.html).
* [Data visualization with Seaborn](https://beta.oreilly.com/learning/data-visualization-with-seaborn) es un recorrido rápido por algunos de los tipos populares de parcelas marinas.
* [Visualizing Google Forms Data with Seaborn](http://pbpython.com/pandas-google-forms-part2.html) y [How to Create NBA Shot Charts in Python](http://savvastjortjoglou.com/nba-shot-sharts.html) son buenos ejemplos de uso de marinas sobre datos del mundo real.

-----

### Clase 9: Evaluación básica del modelo
* Tarea de raspado web opcional adeudado ([solution](code/07_web_scraping.py#L136))
* Reproducibilidad
    * Discuta las lecturas asignadas:[introduction](http://www.dataschool.io/reproducibility-is-not-just-for-researchers/), [Colbert Report video](http://thecolbertreport.cc.com/videos/dcyvro/austerity-s-spreadsheet-error), [cabs article](http://iquantny.tumblr.com/post/107245431809/how-software-in-half-of-nyc-cabs-generates-5-2), [Tweet](https://twitter.com/jakevdp/status/519563939177197571), [creating a reproducible analysis](https://github.com/jtleek/datasharing)
    * Examples: [Classic rock](https://github.com/fivethirtyeight/data/tree/master/classic-rock), [student project 1](https://github.com/jwknobloch/DAT4_final_project), [student project 2](https://github.com/justmarkham/DAT4-students/tree/master/Jonathan_Bryan/Project_Files)
* Discuta la tarea de lectura en el [bias-variance tradeoff](homework/09_bias_variance.md)
* Evaluación del modelo utilizando la división de trenes/pruebas([notebook](notebooks/09_model_evaluation.ipynb))
* Explorando la documentación de Scikit-Learn: [module reference](http://scikit-learn.org/stable/modules/classes.html), [user guide](http://scikit-learn.org/stable/user_guide.html), Documentación de clase y función

* [Data science in Python](https://www.youtube.com/watch?v=3ZWuPVWq7p4) [associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/06_linear_regression.ipynb).
* **Optional:* [The Easiest Introduction to Regression Analysis](https://www.youtube.com/watch?v=k_OB1tWX9PM)

**Recursos de evaluación del modelo**
*Para un resumen de algunos de los puntos clave de la lección de hoy, mira [Comparing machine learning models in scikit-learn](https://www.youtube.com/watch?v=0pP4EwWJgIU)(27 minutos).
* For Otra explicación del error de entrenamiento versus el error de prueba, la compensación de varianza de sesgo y la división de trenes/pruebas (también conocido como "enfoque de conjunto de validación"), mira el video de Hastie y Tibshirani en[estimating prediction error](https://www.youtube.com/watch?v=_2ij6eaaSl0&t=2m34s) (12 minutos, comenzando a las 2:34).
* El aprendizaje de Caltech de los datos incluye un video fantástico en [visualizing bias and variance](http://work.caltech.edu/library/081.html) (15 minutos).
* [Random Test/Train Split is Not Always Enough](http://www.win-vector.com/blog/2015/01/random-testtrain-split-is-not-always-enough/)Explica por qué la división aleatoria de trenes/pruebas puede no ser un procedimiento de evaluación de modelo adecuado si sus datos tienen un elemento de tiempo significativo.

**Recursos de reproducibilidad**
* [What We've Learned About Sharing Our Data Analysis](https://source.opennews.org/en-US/articles/what-weve-learned-about-sharing-our-data-analysis/) Incluye consejos de BuzzFeed News sobre cómo publicar un análisis reproducible.
* [Software development skills for data scientists](http://treycausey.com/software_dev_skills.html) Discute la importancia de escribir funciones y comentarios de código adecuados (entre otras habilidades), que son muy útiles para crear un análisis reproducible.
* [Data science done well looks easy - and that is a big problem for data scientists](http://simplystatistics.org/2015/03/17/data-science-done-well-looks-easy-and-that-is-a-big-problem-for-data-scientists/) Explica cómo un análisis reproducible demuestra todo el trabajo que entra en la ciencia de datos adecuada.

-----

### Clase 10: regresión lineal
* Ejercicio de aprendizaje automático([article](http://blog.dominodatalab.com/10-interesting-uses-of-data-science/))
* Regresión lineal ([notebook](notebooks/10_linear_regression.ipynb))
    * [Capital Bikeshare dataset](data/bikeshare.csv) used in a Kaggle competition
    * [Data dictionary](https://www.kaggle.com/c/bike-sharing-demand/data)
* Ejemplo de ingeniería de características: [Predicting User Engagement in Corporate Collaboration Network](https://github.com/mikeyea/DAT7_project/blob/master/final%20project/Class_Presention_MYea.ipynb)

**Tarea:**
* ¡Su primera presentación del proyecto es el martes (9/22)!Envíe un enlace al repositorio de su proyecto (con diapositivas, código, datos y visualizaciones) a las 6pm del martes.
* Completar la [homework assignment](homework/10_yelp_votes.md) con el [Yelp data](data/yelp.csv). Esto se debe el jueves (9/24).

**Recursos de regresión lineal**
* Para ir mucho más en profundidad sobre la regresión lineal, lea el Capítulo 3 de [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/).Alternativamente, mira el[related videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) o leer mi [quick reference guide](http://www.dataschool.io/applying-and-interpreting-linear-regression/) a los puntos clave en ese capítulo.
* Esta[introduction to linear regression](http://people.duke.edu/~rnau/regintro.htm) es más detallado y matemáticamente minucioso, e incluye muchos buenos consejos.
* Esta es una publicación relativamente rápida en el [assumptions of linear regression](http://pareonline.net/getvn.asp?n=2&v=8).
*Setosa tiene un [interactive visualization](http://setosa.io/ev/ordinary-least-squares-regression/) of regresión lineal.
* Para una breve introducción a los intervalos de confianza, las pruebas de hipótesis, los valores P y el R-cuadrado, así como una comparación entre el código de Scikit-Learn y [Statsmodels](http://statsmodels.sourceforge.net/) code, leer mi [DAT7 lesson on linear regression](https://github.com/justmarkham/DAT7/blob/master/notebooks/10_linear_regression.ipynb).
* Aquí hay una explicación útil de [confidence intervals](http://www.quora.com/What-is-a-confidence-interval-in-laymans-terms/answer/Michael-Hochster) de Quora.
* [Hypothesis Testing: The Basics](http://20bits.com/article/hypothesis-testing-the-basics) proporciona una buena visión general del tema, y ​​la charla de John Rauser en [Statistics Without the Agonizing Pain](https://www.youtube.com/watch?v=5Dnw46eC-0o) (12 minutos) da una gran explicación de cómo se rechaza la hipótesis nula.
* A principios de este año, una importante revista científica prohibió el uso de valores P:
* Scientific American tiene un buen [summary](http://www.scientificamerican.com/article/scientists-perturbed-by-loss-of-stat-tools-to-sift-research-fudge-from-fact/) of the ban.
    * Esta [response](http://www.nature.com/news/statistics-p-values-are-just-the-tip-of-the-iceberg-1.17412) A la prohibición de la naturaleza argumenta que "las decisiones que se toman anteriormente en el análisis de datos tienen un impacto mucho mayor en los resultados".
    * Andrew Gelman tiene un legible [paper](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf)en el que argumenta que "es fácil encontrar una comparación P <.05 incluso si no está sucediendo nada, si miras lo suficiente".
    * [Science Isn't Broken](http://fivethirtyeight.com/features/science-isnt-broken/) iIncluye una herramienta ordenada que le permite "P-Hack" su camino hacia los resultados "estadísticamente significativos".
* [Accurately Measuring Model Prediction Error](http://scott.fortmann-roe.com/docs/MeasuringError.html) Compara R-cuadrado ajustado, AIC y BIC, división de tren/prueba y validación cruzada.
**Otros recursos:**
* Sección 3.3.1 de [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (4 pages)Tiene una gran explicación de la codificación ficticia para características categóricas.
* Kaggle tiene algo agradable [visualizations of the bikeshare data](https://www.kaggle.com/c/bike-sharing-demand/scripts?outputType=Visualization) Usamos hoy.

-----

### Clase 11: Presentación del primer proyecto
* ¡Presentaciones del proyecto!

**Tarea:**
* Mira los videos de Rahul Patwari en [Probabilidad] (https://www.youtube.com/watch?v=o4qmonfw3bi) (5 minutos) y [probabilidades] (https://www.youtube.com/watch?v=GXBXQJX7FC0) (8 minutos) Si no se siente cómodo con ninguno de esos términos.
* Lea estos excelentes artículos de BetterExplained: [una guía intuitiva de funciones exponenciales y e] (http://betterexplained.com/articles/an-intuitive-guide-to-exponential-functions-e/) y [desmystificación del logaritmo natural(ln)] (http://betterexplained.com/articles/demystifying-the-natural-logarithm-ln/).Luego, revise este [breve resumen] (cuadernos/12_e_log_examples.ipynb) of exponential functions and logarithms.

-----

### Clase 12: Regresión logística
* Yelp Votes Tarea Due ([Solución] (cuadernos/10_yelp_votes_homework.ipynb))
* Regresión logística ([cuaderno] (cuadernos/12_logistic_regression.ipynb))
* [Conjunto de datos de identificación de vidrio] (https://archive.ics.uci.edu/ml/datasets/glass+identification)
* Ejercicio con Titanic Data ([cuaderno] (cuaderno/12_titanic_confusion.ipynb), [data] (data/titanic.csv), [Data Dictionary] (https://www.kaggle.com/c/titanic/data)))
* Confusion Matrix ([diapositivas] (diapositivas/12_confusion_matrix.pdf), [cuaderno] (cuaderno/12_titanic_confusion.ipynb)))

**Tarea:**
* Si aún no se siente cómodo con toda la terminología de la matriz de confusión, mire los videos de Rahul Patwari en [Sensibilidad y especificidad intuitiva] (https://www.youtube.com/watch?v=U4_3fditnwg) (9 minutos) y [[9 minutos) y [[9 minutos) y [[La compensación entre sensibilidad y especificidad] (https://www.youtube.com/watch?v=vtydyggeqyo) (13 minutos).
* Asignación de video/lectura en [curvas ROC y AUC] (tarea/13_roc_auc.md)
* Asignación de video/lectura en [Validación cruzada] (tarea/13_cross_validation.md)

**Recursos de regresión logística:**
* Para profundizar en la regresión logística, lea las primeras tres secciones del Capítulo 4 de [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/),O mira el [first three videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) (30 minutos) de ese capítulo.
* Para una explicación matemática de la regresión logística, mire los primeros siete videos (71 minutos) de la semana 3 de Andrew Ng's [machine learning course](https://www.coursera.org/learn/machine-learning/home/info), o leer el [related lecture notes](http://www.holehouse.org/mlclass/06_Logistic_Regression.html) compilado por un estudiante.
* Para obtener más información sobre la interpretación de los coeficientes de regresión logística, lea este excelente [guide](http://www.ats.ucla.edu/stat/mult_pkg/faq/general/odds_ratio.htm)por el idre de UCLA y estos [lecture notes](http://www.unm.edu/~schrader/biostat/bio2/Spr06/lec11.pdf) de la Universidad de Nuevo México.
* TLa documentación de Scikit-Learn tiene una buena [explanation](http://scikit-learn.org/stable/modules/calibration.html) de lo que significa para una probabilidad prevista para ser calibrada.
* [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html)es una muy buena comparación de cuatro clasificadores que cubrimos en el curso (regresión logística, árboles de decisión, KNN, Naive Bayes) y un clasificador que no cubrimos (Máquinas de vectores de soporte).

**Recursos de matriz de confusión:**
* Mi [simple guide to confusion matrix terminology](http://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/) Puede ser útil para usted como referencia.
*Esta publicación de blog sobre [Amazon Machine Learning](https://aws.amazon.com/blogs/aws/amazon-machine-learning-make-data-driven-decisions-at-scale/) Contiene un ordenado [graphic](https://media.amazonwebservices.com/blog/2015/ml_adjust_model_1.png) Mostrar cómo el umbral de clasificación afecta diferentes métricas de evaluación.
* Este cuaderno (de otro curso de datos) explicas [how to calculate "expected value"](https://github.com/podopie/DAT18NYC/blob/master/classes/13-expected_value_cost_benefit_analysis.ipynb) fROM una matriz de confusión tratándola como una matriz de costo-beneficio.

-----

### Clase 13: Evaluación avanzada del modelo
* Preparación de datosn ([notebook](notebooks/13_advanced_model_evaluation.ipynb))
    * Manejo de valores faltantes
    * Manejo de características categóricas (revisión)
* Curvas ROC y AUC
    * Discutir el[video/reading assignment](homework/13_roc_auc.md)
    * Ejercicio: dibujar una curva ROC ([slides](slides/13_drawing_roc.pdf))
    * Volver al cuaderno principal
* Validación cruzada
    * Discutir el [video/reading assignment](homework/13_cross_validation.md) and associated [notebook](notebooks/13_cross_validation.ipynb)
    * Volver al cuaderno principal
* Eejercicio con datos de marketing bancario ([notebook](notebooks/13_bank_exercise.ipynb), [data](data/bank-additional.csv), [data dictionary](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing))

**Tareak:**
* Tarea de lectura on [spam filtering](homework/14_spam_filtering.md)
* Lee esto [Introduction to Probability](https://docs.google.com/presentation/d/1cM2dVbJgTWMkHoVNmYlB9df6P2H8BrjaqAcZTaLe9dA/edit#slide=id.gfc3caad2_00) slides, or skim section 2.1 of the [OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php?stat_book=os) (12 pages).Preste atención específica a los siguientes términos: probabilidad, mutuamente excluyente, espacio muestral, independiente.
* **Opcional:** Intente obtener una comprensión de la probabilidad condicional de este [visualization](http://setosa.io/conditional/).
* **Opcional:** Para una introducción intuitiva al teorema de Bayes, lea estas publicaciones en [wealth and happiness](http://www.quora.com/What-is-an-intuitive-explanation-of-Bayes-Rule/answer/Michael-Hochster), [ducks](https://planspacedotorg.wordpress.com/2014/02/23/bayes-rule-for-ducks/), o [legos](http://www.countbayesie.com/blog/2015/2/18/bayes-theorem-with-lego).

**Recursos ROC:**
* Rahul Patwari tiene un gran video [ROC Curves](https://www.youtube.com/watch?v=21Igj5Pr6u4) (12 minutos).
* [An introduction to ROC analysis](http://people.inf.elte.hu/kiss/13dwhdm/roc.pdf) es un artículo muy legible sobre el tema.
* Las curvas ROC se pueden usar en una amplia variedad de aplicaciones, como [comparing different feature sets](http://research.microsoft.com/pubs/205472/aisec10-leontjeva.pdf) para detectar usuarios fraudulentos de Skype, y[comparing different classifiers](http://www.cse.ust.hk/nevinZhangGroup/readings/yi/Bradley_PR97.pdf)en varios conjuntos de datos populares.

**Recursos de validación cruzada:**
* Para obtener más información sobre la validación cruzada, lea la sección 5.1 de [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (11 páginas) o ver los videos relacionados: [K-fold and leave-one-out cross-validation](https://www.youtube.com/watch?v=nZAM5OXrktY) (14 minutos), [cross-validation the right and wrong ways](https://www.youtube.com/watch?v=S06JpVoNaA0) (10 minutos).
* Si desea comprender las diferentes variaciones de validación cruzada, esto [paper](http://www.jcheminf.com/content/pdf/1758-2946-6-10.pdf) Los examina y los compara en detalle.
* Para aprender a usar [GridSearchCV and RandomizedSearchCV](http://scikit-learn.org/stable/modules/grid_search.html) Para el ajuste de los parámetros, mira [How to find the best model parameters in scikit-learn](https://www.youtube.com/watch?v=Gol_qOgRqfA) (28 minutos) o lea el [associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/08_grid_search.ipynb).

**Otros recursos:**
* Scikit-Learn tiene una amplia documentación en [model evaluation](http://scikit-learn.org/stable/modules/model_evaluation.html).
* [Evaluación contrafactual de modelos de aprendizaje automático](https://www.youtube.com/watch?v=QWCSxAKR-h0) (45 minutos) es una excelente charla sobre la forma sofisticada en que Stripe evalúa su modelo de detección de fraude.(Estos son los asociados [slides](http://www.slideshare.net/MichaelManapat/counterfactual-evaluation-of-machine-learning-models).)
* [Visualizar los umbrales de aprendizaje automático para tomar mejores decisiones comerciales](http://blog.insightdatalabs.com/visualizing-classifier-thresholds/) dEmonstruye cómo la visualización de la precisión, el retiro y la "tasa de cola" en diferentes umbrales pueden ayudarlo a maximizar el valor comercial de su clasificador.

-----

###Clase 14: Naive Bayes and Text Data
*Probabilidad condicional y teorema de Bayes
    * [Slides](slides/14_bayes_theorem.pdf) (adaptado de [Visualizing Bayes' theorem](http://oscarbonilla.com/2009/05/visualizing-bayes-theorem/))
    * Aplicar el teorema de Bayes a la clasificación de Iris([notebook](notebooks/14_bayes_theorem_iris.ipynb))
* Naive Bayes classification
    * [Slides](slides/14_naive_bayes.pdf)
    * Spam filtering example ([notebook](notebooks/14_naive_bayes_spam.ipynb))
* AplicandoNaive Bayes Para enviar datos de texto en Scikit-Learn ([notebook](notebooks/14_text_data_sklearn.ipynb))
    * [CountVectorizer](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html) documentation
    * SMS messages: [data](data/sms.tsv), [data dictionary](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

**Tarea:**
* Completar otro [homework assignment](homework/14_yelp_review_text.md) con el [Yelp data](data/yelp.csv). Esto se debe el martes (10/6).
* Confirma que tienes [TextBlob](https://textblob.readthedocs.org/) instalado ejecutando`import textblob` desde dentro de su entorno Python preferido.Si no está instalado, ejecute`pip install textblob` en la línea de comando (no desde dentro de Python).

**Recursos:**
* Artículo de Sebastian Rakka en [Naive Bayes and Text Classification](http://sebastianraschka.com/Articles/2014_naive_bayes_1.html) Cubre el material conceptual de la clase de hoy con mucho más detalle.
* Para obtener más información sobre probabilidad condicional, lea estos [slides](https://docs.google.com/presentation/d/1psUIyig6OxHQngGEHr3TMkCvhdLInnKnclQoNUr4G4U/edit#slide=id.gfc69f484_00), o leer la sección 2.2 del[OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php?stat_book=os) (15 páginas).
*Para una explicación intuitiva de la clasificación de Naive Bayes, lea esta publicación en [airport security](http://www.quora.com/In-laymans-terms-how-does-Naive-Bayes-work/answer/Konstantin-Tt).
* Para más detalles sobre la clasificación de Naive Bayes, Wikipedia tiene dos artículos excelentes([Naive Bayes classifier](http://en.wikipedia.org/wiki/Naive_Bayes_classifier) y [Naive Bayes spam filtering](http://en.wikipedia.org/wiki/Naive_Bayes_spam_filtering)),Y Cross Valided tiene un buen[Q&A](http://stats.stackexchange.com/questions/21822/understanding-naive-bayes).
* Al aplicar la clasificación ingenua de Bayes a un conjunto de datos con características continuas, es mejor usarlo [GaussianNB](http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html) en vez de[MultinomialNB](http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html). Esta [notebook](notebooks/14_types_of_naive_bayes.ipynb) Compara sus actuaciones en dicho conjunto de datos.Wikipedia tiene un corto[description](https://en.wikipedia.org/wiki/Naive_Bayes_classifier#Gaussian_naive_Bayes)de Bayes ingenuos gaussianos, así como un excelente [example](https://en.wikipedia.org/wiki/Naive_Bayes_classifier#Sex_classification) de su uso.
*Estas[slides](http://www.umiacs.umd.edu/~jbg/teaching/DATA_DIGGING/lecture_05.pdf) De la Universidad de Maryland, proporcione más detalles matemáticos sobre la regresión logística y los bayes ingenuos, y también explique cómo Naive Bayes es en realidad un "caso especial" de regresión logística.
* Andrew Ng tiene un [paper](http://ai.stanford.edu/~ang/papers/nips01-discriminativegenerative.pdf) Comparando el rendimiento de la regresión logística y los bayes ingenuos en una variedad de conjuntos de datos.
* Si disfrutas el artículo de Paul Graham, puedes leer[his follow-up article](http://www.paulgraham.com/better.html) sobre cómo mejoró su filtro de spam y esto [related paper](http://www.merl.com/publications/docs/TR2004-091.pdf) sobre el filtrado de spam de última generación en 2004.
* YELP ha descubierto que Naive Bayes es más efectivo que los turcos mecánicos en [categorizing businesses](http://engineeringblog.yelp.com/2011/02/towards-building-a-high-quality-workforce-with-mechanical-turk.html).

-----

### Clase 15: Procesamiento del lenguaje natural
* Tarea de texto de revisión de Yelp debido ([solution](notebooks/14_yelp_review_text_homework.ipynb))
* Procesamiento natural del lenguaje ([notebook](notebooks/15_natural_language_processing.ipynb))
* Introducción a nuestro [Kaggle competition](https://inclass.kaggle.com/c/dat8-stack-overflow)
    *Cree una cuenta de Kaggle, únase a la competencia utilizando el enlace de invitación, descargue el envío de la muestra y luego envíe el envío de muestra (que requerirá la verificación de la cuenta de SMS).

**Tarea:**
* ¡Su documento de borrador debe vencer el jueves (10/8)!Envíe un enlace al repositorio de su proyecto (con papel, código, datos y visualizaciones) antes de la clase.
*Mirar[Kaggle: How it Works](https://www.youtube.com/watch?v=PoD84TVdD-4) (4 minutos) para una breve descripción de la plataforma Kaggle.
* Descargue los archivos de competencia, muévalos al `DAT8/data` dIrectory, y asegúrese de que pueda abrir los archivos CSV con PANDAS.Si tiene algún problema para abrir los archivos, probablemente necesite desactivar el escaneo de virus en tiempo real (especialmente Microsoft Security Essentials).
* **Opcional:** Elige algunas teorías sobre qué características pueden ser relevantes para predecir la respuesta, y luego explorar los datos para ver si esas teorías parecen ser ciertas.
* **Opcional:** Mira My [project presentation video](https://www.youtube.com/watch?v=HGr1yQV3Um0) (16 minutos) para un recorrido por el proceso de aprendizaje automático de extremo a extremo para una competencia de Kaggle, incluida la ingeniería de características.(O, solo lea el [slides](https://speakerdeck.com/justmarkham/allstate-purchase-prediction-challenge-on-kaggle).)

**Recursos de PNL:**
* Si quieres aprender mucho más PNL, mira el excelente [video lectures](https://class.coursera.org/nlp/lecture) and [slides](http://web.stanford.edu/~jurafsky/NLPCourseraSlides.html) from this [Coursera course](https://www.coursera.org/course/nlp) (que ya no se ofreced).
* Este mazo de diapositivas define muchos de los [key NLP terms](https://github.com/ga-students/DAT_SF_9/blob/master/16_Text_Mining/DAT9_lec16_Text_Mining.pdf).
* [Natural Language Processing with Python](http://www.nltk.org/book/) es el libro más popular para ir profundamente con el[Natural Language Toolkit](http://www.nltk.org/) (NLTK).
* [A Smattering of NLP in Python](https://github.com/charlieg/A-Smattering-of-NLP-in-Python/blob/master/A%20Smattering%20of%20NLP%20in%20Python.ipynb) proporciona una buena descripción de NLTK, al igual que esto [notebook from DAT5](https://github.com/justmarkham/DAT5/blob/master/notebooks/14_nlp.ipynb).
* [spaCy](http://spacy.io/) es una biblioteca de Python más nueva para el procesamiento de texto que se centra en el rendimiento (a diferencia de NLTK).
* Si quieres tomarte en serio sobre NLP, [Stanford CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml) es un conjunto de herramientas (escritas en Java) que es muy apreciada.
*Cuando trabaja con un cuerpo de texto grande en Scikit-Learn, [HashingVectorizer](http://scikit-learn.org/stable/modules/feature_extraction.html#vectorizing-a-large-text-corpus-with-the-hashing-trick)es una alternativa útil a CountVectorizer.
* [Automatically Categorizing Yelp Businesses](http://engineeringblog.yelp.com/2015/09/automatically-categorizing-yelp-businesses.html) Discute cómo Yelp usa NLP y Scikit-Learn para resolver el problema de las empresas no categorizadas.
* [Modern Methods for Sentiment Analysis](http://districtdatalabs.silvrback.com/modern-methods-for-sentiment-analysis) Muestra cómo se pueden usar "vectores de palabras" para un análisis de sentimientos más preciso.
* [Identifying Humorous Cartoon Captions](http://www.cs.huji.ac.il/~dshahaf/pHumor.pdf) iS un artículo legible sobre la identificación de subtítulos divertidos presentados al concurso de subtítulos de New Yorker.
* [DC Natural Language Processing](http://www.meetup.com/DC-NLP/) es un grupo de reunión activo en nuestra área local.

-----

### Clase 16: Competencia de Kaggle
* Descripción general de cómo funciona Kaggle ([slides](slides/16_kaggle.pdf))
* Competencia en clase Kaggle: [Predict whether a Stack Overflow question will be closed](https://inclass.kaggle.com/c/dat8-stack-overflow)
    * [Complete code file](code/16_kaggle.py)
    * [Minimal code file](code/16_kaggle_minimal.py): excludes all exploratory code
    * [Explanations of log loss](http://www.quora.com/What-is-an-intuitive-explanation-for-the-log-loss-function)

**Homework:**
* Se le asignará para revisar los borradores del proyecto de dos de sus pares.Tiene hasta el martes 10/20 para proporcionarles comentarios, según el[peer review guidelines](project/peer_review.md).
* Leer [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) para una breve descripción de los árboles de decisión.
* Descargar e instalar[Graphviz](http://www.graphviz.org/), que le permitirá visualizar los árboles de decisión en Scikit-Learn.
    * Los usuarios de Windows también deben agregar GraphViz a su ruta: vaya al panel de control, el sistema, la configuración avanzada del sistema, las variables de entorno.En Variables del sistema, edite "ruta" para incluir la ruta a la carpeta "bin", como: `C:\Program Files (x86)\Graphviz2.38\bin`
* **Opcional:** ¡Sigue trabajando en nuestra competencia de Kaggle!Puede formar hasta 5 presentaciones por día, y la competencia no se cierre hasta las 6:30 p.m. ET del martes 27/11 (Clase 21).

**Recursos:**
* [Specialist Knowledge Is Useless and Unhelpful](http://www.slate.com/articles/health_and_science/new_scientist/2012/12/kaggle_president_jeremy_howard_amateurs_beat_specialists_in_data_prediction.html) es una breve entrevista con Jeremy Howard (ex presidente de Kaggle) en la que argumenta que las habilidades de ciencia de datos son mucho más importantes que la experiencia de dominio para crear modelos predictivos efectivos.
* [Getting in Shape for the Sport of Data Science](https://www.youtube.com/watch?v=kwt6XEh7U3g) (74 minutos), también por Jeremy Howard, contiene muchos consejos para el aprendizaje automático competitivo.
* [Learning from the best](http://blog.kaggle.com/2014/08/01/learning-from-the-best/) es una excelente publicación de blog que cubre los mejores consejos de Kaggle Masters sobre cómo hacerlo bien en Kaggle.
* [Feature Engineering Without Domain Expertise](https://www.youtube.com/watch?v=bL4b1sGnILU) (17 minutos), una charla del maestro de Kaggle Nick Kridler, proporciona algunos consejos simples sobre cómo iterar rápidamente y dónde pasar su tiempo durante una competencia de Kaggle.
*Estos ejemplos pueden ayudarlo a comprender mejor el proceso de ingeniería de características: predecir el número de [passengers at a train station](https://medium.com/@chris_bour/french-largest-data-science-challenge-ever-organized-shows-the-unreasonable-effectiveness-of-open-8399705a20ef), identifying [fraudulent users of an online store](https://docs.google.com/presentation/d/1UdI5NY-mlHyseiRVbpTLyvbrHxY8RciHp5Vc-ZLrwmU/edit#slide=id.p), identifying [bots in an online auction](https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/forums/t/14628/share-your-secret-sauce), predicting who will [subscribe to the next season of an orchestra](http://blog.kaggle.com/2015/01/05/kaggle-inclass-stanfords-getting-a-handel-on-data-science-winners-report/), y evaluar el [quality of e-commerce search engine results](http://blog.kaggle.com/2015/07/22/crowdflower-winners-interview-3rd-place-team-quartet/).
* [Our perfect submission](https://www.kaggle.com/c/restaurant-revenue-prediction/forums/t/13950/our-perfect-submission) es una lectura divertida sobre cuán gran rendimiento en el [public leaderboard](https://www.kaggle.com/c/restaurant-revenue-prediction/leaderboard/public) no garantiza que un modelo se generalice a nuevos datos.

-----

### Clase 17: Árboles de decisión
* Árboles de decisión ([notebook](notebooks/17_decision_trees.ipynb))
* Ejercicio con los datos de Bikeshare de Capital([notebook](notebooks/17_bikeshare_exercise.ipynb), [data](data/bikeshare.csv), [data dictionary](https://www.kaggle.com/c/bike-sharing-demand/data))

**Tarea:**
* Lea la sección "Sabiduría de las multitudes" de la publicación de Mlwave en [Human Ensemble Learning](http://mlwave.com/human-ensemble-learning/).
* **Optional:** Leer el resumen de [Do We Need Hundreds of Classifiers to Solve Real World Classification Problems?](http://jmlr.csail.mit.edu/papers/volume15/delgado14a/delgado14a.pdf), aS como Kaggle CTO Ben Namner's [comment](https://news.ycombinator.com/item?id=8719723) sobre el documento, prestando atención a las menciones de "bosques aleatorios".

**Recursos:**
* La documentación de Scikit-Learn en [decision trees](http://scikit-learn.org/stable/modules/tree.html) Incluye una buena descripción de los árboles, así como consejos para el uso adecuado.
* Para una introducción más exhaustiva a los árboles de decisión, lea la Sección 4.3 (23 páginas) de [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php). (El Capítulo 4 está disponible como descarga gratuita).
* Si quieres profundizar en los diferentes algoritmos de árbol de decisión, este mazo de diapositivas contiene [A Brief History of Classification and Regression Trees](https://drive.google.com/file/d/0B-BKohKl-jUYQ3RpMEF0OGRUU3RHVGpHY203NFd3Z19Nc1ZF/view).
* [The Science of Singing Along](http://www.doc.gold.ac.uk/~mas03dm/papers/PawleyMullensiefen_Singalong_2012.pdf) Contiene un árbol de regresión ordenado (página 136) para predecir el porcentaje de una audiencia en un lugar de música que cantará junto con una canción pop.
* Los árboles de decisión son comunes en el campo de la medicina para el diagnóstico diferencial, como este árbol de clasificación para [identifying psychosis](http://www.psychcongress.com/sites/naccme.com/files/images/pcn/saundras/psychosis_decision_tree.pdf).

-----

### Clase 18: Ensembling
* Lección de árboles de decisión de finalización([notebook](notebooks/17_decision_trees.ipynb))
* Conjunto ([notebook](notebooks/18_ensembling.ipynb))
    * [Major League Baseball player data](data/hitters.csv) from 1986-87
    * [Data dictionary](https://cran.r-project.org/web/packages/ISLR/ISLR.pdf) (page 7)

**Recursos:**
* La documentación de Scikit-Learn en [ensemble methods](http://scikit-learn.org/stable/modules/ensemble.html) cubre tanto los "métodos de promedio" (como el bolso y los bosques aleatorios), así como los "métodos de impulso" (como el impulso de Adaaboost y Gradient Tree).
*Mlwave[Kaggle Ensembling Guide](http://mlwave.com/kaggle-ensembling-guide/) es muy minucioso y muestra las diferentes formas en que puede tener lugar el conjunto.
* Explorar lo excelente [solution paper](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/ChenglongChen/Kaggle_CrowdFlower/master/Doc/Kaggle_CrowdFlower_ChenglongChen.pdf) del ganador de Kaggle's[CrowdFlower competition](https://www.kaggle.com/c/crowdflower-search-relevance) fO un ejemplo del trabajo y la visión necesaria para ganar una competencia de Kaggle.
* [Interpretable vs Powerful Predictive Models: Why We Need Them Both](https://medium.com/@chris_bour/interpretable-vs-powerful-predictive-models-why-we-need-them-both-990340074979) Es una breve publicación sobre cómo las tácticas útiles en una competencia de Kaggle no siempre son útiles en el mundo real.
* [Not Even the People Who Write Algorithms Really Know How They Work](http://www.theatlantic.com/technology/archive/2015/09/not-even-the-people-who-write-algorithms-really-know-how-they-work/406099/) Argumenta que la disminución de la interpretabilidad de los modelos de aprendizaje automático de última generación tiene un impacto negativo en la sociedad.
* Para una explicación intuitiva de los bosques aleatorios, lea la respuesta de Edwin Chen a [How do random forests work in layman's terms?](http://www.quora.com/Random-Forests/How-do-random-forests-work-in-laymans-terms/answer/Edwin-Chen-1)
* [Large Scale Decision Forests: Lessons Learned](http://blog.siftscience.com/blog/2015/large-scale-decision-forests-lessons-learned) es una excelente publicación de Sift Science sobre su implementación personalizada de bosques aleatorios.
* [Unboxing the Random Forest Classifier](http://nerds.airbnb.com/unboxing-the-random-forest-classifier/)Describe una forma de interpretar el funcionamiento interno de los bosques aleatorios más allá de las importantes importantes.
* [Understanding Random Forests: From Theory to Practice](http://arxiv.org/pdf/1407.7502v3.pdf) es un análisis académico en profundidad de bosques aleatorios, incluidos los detalles de su implementación en Scikit-Learn.

-----

### Clase 19: Scikit-learn y Clustering avanzado
* Advanced scikit-learn ([notebook](notebooks/19_advanced_sklearn.ipynb))
    * [StandardScaler](http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html): standardizing features
    * [Pipeline](http://scikit-learn.org/stable/modules/pipeline.html): chaining steps
* Clustering ([slides](slides/19_clustering.pdf), [notebook](notebooks/19_clustering.ipynb))
    * K-means: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html), [visualization 1](http://tech.nitoyon.com/en/blog/2013/11/07/k-means/), [visualization 2](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
    * DBSCAN: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html), [visualization](http://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)

**Tarea:**
* Releer[Understanding the Bias-Variance Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html). (The "answers" to the [guiding questions](homework/09_bias_variance.md) he sido publicado y puede ser útil para usted).
* **Opcional:** Mire estos dos videos excelentes (y relacionados) del curso de Aprendizaje de Data de Caltech: [bias-variance tradeoff](http://work.caltech.edu/library/081.html) (15 minutos) y [regularization](http://work.caltech.edu/library/121.html) (8 minutos).

**recursos de Scikit-Learn:**
* Este es un ejemplo más largo de [feature scaling](https://github.com/rasbt/pattern_classification/blob/master/preprocessing/about_standardization_normalization.ipynb) En Scikit-Learn, con una discusión adicional de los tipos de escala que puede usar.
* [Practical Data Science in Python](http://radimrehurek.com/data_science_python/) iS un cuaderno largo y bien escrito que utiliza algunas características avanzadas de Scikit-Learn: tuberías, trazar una curva de aprendizaje y encurtir un modelo.
* Para aprender a usar [GridSearchCV and RandomizedSearchCV](http://scikit-learn.org/stable/modules/grid_search.html) Para el ajuste de los parámetros, mira[How to find the best model parameters in scikit-learn](https://www.youtube.com/watch?v=Gol_qOgRqfA) (28 minutos) o lea el[associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/08_grid_search.ipynb).
* Sebastian Raschka tiene una serie de excelentes recursos para los usuarios de Scikit-Learn, incluido un repositorio de[tutorials and examples](https://github.com/rasbt/pattern_classification), Una biblioteca de aprendizaje automático [tools and extensions](http://rasbt.github.io/mlxtend/), a new [book](https://github.com/rasbt/python-machine-learning-book), y un semi-activo [blog](http://sebastianraschka.com/blog/).
* Scikit-Learn tiene un increíblemente activo [mailing list](https://www.mail-archive.com/scikit-learn-general@lists.sourceforge.net/index.html) Eso a menudo es mucho más útil que el desbordamiento de la pila para investigar las funciones y hacer preguntas.
* Si olvida cómo usar una función particular de Scikit-Learn que hemos usado en la clase, ¡no olvide que este repositorio es completamente búsqueda!

**Recursos de Clustering:**
* Para una introducción muy exhaustiva a la agrupación, lea el Capítulo 8 (69 páginas) de [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php) (Disponible como descarga gratuita), o navegar a través de las diapositivas del Capítulo 8.
* Guía del usuario de Scikit-Learn compara muchos diferentes[types of clustering](http://scikit-learn.org/stable/modules/clustering.html).
* Esta[PowerPoint presentation](http://www2.research.att.com/~volinsky/DataMining/Columbia2011/Slides/Topic6-Clustering.ppt) De la clase de minería de datos de Columbia proporciona una buena introducción a la agrupación, incluida la agrupación jerárquica y las métricas de distancia alternativa.
* Una introducción al aprendizaje estadístico tiene videos útiles sobre[K-means clustering](https://www.youtube.com/watch?v=aIybuNt9ps4&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2)(17 minutos) y [hierarchical clustering](https://www.youtube.com/watch?v=Tuuc9Y06tAc&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2) (15 minutos).
* Esta es una excelente visualización interactiva de [hierarchical clustering](https://joyofdata.shinyapps.io/hclust-shiny/).
* Esta es una buena explicación animada de[mean shift clustering](http://spin.atomicobject.com/2015/05/26/mean-shift-clustering/).
* La [K-modes algorithm](http://www.cs.ust.hk/~qyang/Teaching/537/Papers/huang98extensions.pdf) Se puede utilizar para agrupar conjuntos de datos de características categóricas sin convertirlos en valores numéricos.Aquí hay una [implementación de Python] (https://github.com/nicodv/kmodes).
* Aquí hay algunos ejemplos divertidos de agrupación: [A Statistical Analysis of the Work of Bob Ross](http://fivethirtyeight.com/features/a-statistical-analysis-of-the-work-of-bob-ross/) (with [data and Python code](https://github.com/fivethirtyeight/data/tree/master/bob-ross)), [How a Math Genius Hacked OkCupid to Find True Love](http://www.wired.com/2014/01/how-to-hack-okcupid/all/), and [characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/).

-----

### Clase 20: Regularización y expresiones regulares
* Regularización ([notebook](notebooks/20_regularization.ipynb))
    * Regresión: [Ridge](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html), [RidgeCV](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeCV.html), [Lasso](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html), [LassoCV](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LassoCV.html)
    * Clasificación: [LogisticRegression](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
    * Funciones de ayudante: [Pipeline](http://scikit-learn.org/stable/modules/pipeline.html), [GridSearchCV](http://scikit-learn.org/stable/modules/grid_search.html)
* Expresiones regulares
    * [Baltimore homicide data](data/homicides.txt)
    * [Regular expressions 101](https://regex101.com/#python): real-time testing of regular expressions
    * [Reference guide](code/20_regex_reference.py)
    * [Exercise](code/20_regex_exercise.py)

**Tarea:**
* ¡Su proyecto final se presentará la próxima semana!
* **Opcional:** ¡Haga sus presentaciones finales a nuestra competencia de Kaggle!Cierra a las 6:30 pm ET el martes 27/10.
* **Opcional:** Lea este artículo clásico, que puede ayudarlo a conectar muchos de los temas que hemos estudiado durante todo el curso: [A Few Useful Things to Know about Machine Learning](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf).

**Recurso de regularizacións:**
* La guía del usuario de Scikit-Learn para[Generalized Linear Models](http://scikit-learn.org/stable/modules/linear_model.html) explica diferentes variaciones de regularización.
* Sección 6.2 de [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (14 páginas) introduces both lasso and ridge regression. Or, watch the related videos on [ridge regression](https://www.youtube.com/watch?v=cSKzqb0EKS0&list=PL5-da3qGB5IB-Xdpj_uXJpLGiRfv9UVXI&index=6) (13 minutos) and [lasso regression](https://www.youtube.com/watch?v=A5I1G1MfUmA&index=7&list=PL5-da3qGB5IB-Xdpj_uXJpLGiRfv9UVXI) (15 minutos).
* Para más detalles sobre la regresión de Lasso, lea Tibshirani[original paper](http://statweb.stanford.edu/~tibs/lasso/lasso.pdf).
* Para una explicación matemática de regularización, mire los últimos cuatro videos (30 minutos) de la semana 3 de Andrew Ng's[machine learning course](https://www.coursera.org/learn/machine-learning/), o leer el[related lecture notes](http://www.holehouse.org/mlclass/07_Regularization.html) compilado por un estudiante.
* Esta [notebook](https://github.com/luispedro/PenalizedRegression/blob/master/PenalizedRegression.ipynb) Del capítulo 7 de[Building Machine Learning Systems with Python](https://www.packtpub.com/big-data-and-business-intelligence/building-machine-learning-systems-python) Tiene un buen ejemplo largo de regresión lineal regularizada.
* Hay algunas consideraciones especiales al usar la codificación ficticia para características categóricas con un modelo regularizado.Este [Cross Validated Q&A](https://stats.stackexchange.com/questions/69568/whether-to-rescale-indicator-binary-dummy-predictors-for-lasso) debates si las variables ficticias deben estandarizarse (junto con el resto de las características), y un comentario sobre esto [blog post](http://appliedpredictivemodeling.com/blog/2013/10/23/the-basics-of-encoding-categorical-data-for-predictive-models) Recomienda que el nivel de referencia no se elimine.

**Regular Expressions Resources:**
* Google's Python Class includes an excellent [introductory lesson](https://developers.google.com/edu/python/regular-expressions) on regular expressions (which also has an associated [video](https://www.youtube.com/watch?v=kWyoYtvJpe4&index=4&list=PL5-da3qGB5IA5NwDxcEJ5dvt8F9OQP7q5)).
* Python for Informatics has a nice [chapter](http://www.pythonlearn.com/html-270/book012.html) on regular expressions. (If you want to run the examples, you'll need to download [mbox.txt](http://www.py4inf.com/code/mbox.txt) and [mbox-short.txt](http://www.py4inf.com/code/mbox-short.txt).)
* [Breaking the Ice with Regular Expressions](https://www.codeschool.com/courses/breaking-the-ice-with-regular-expressions/) is an interactive Code School course, though only the first "level" is free.
* If you want to go really deep with regular expressions, [RexEgg](http://www.rexegg.com/) includes endless articles and tutorials.
* [5 Tools You Didn't Know That Use Regular Expressions](http://blog.codeschool.io/2015/07/30/5-tools-you-didnt-know-that-use-regular-expressions/) demonstrates how regular expressions can be used with Excel, Word, Google Spreadsheets, Google Forms, text editors, and other tools.
* [Exploring Expressions of Emotions in GitHub Commit Messages](http://geeksta.net/geeklog/exploring-expressions-emotions-github-commit-messages/) is a fun example of how regular expressions can be used for data analysis, and [Emojineering](http://instagram-engineering.tumblr.com/post/118304328152/emojineering-part-2-implementing-hashtag-emoji) explains how Instagram uses regular expressions to detect emoji in hashtags.

-----

### Clase 21: Revisión del curso y presentación final del proyecto
* ¡Presentaciones del proyecto!
* [Data science review](https://docs.google.com/document/d/19gBCkmrbMpFFLPX8wa5daMnyl7J5BXhMV8JNJwgp1pk/edit?usp=sharing)

**Recursos:**
* scikitLearn's [machine learning map](http://scikit-learn.org/stable/tutorial/machine_learning_map/) Puede ayudarlo a elegir el "mejor" modelo para su tarea.
* [Choosing a Machine Learning Classifier](http://blog.echen.me/2011/04/27/choosing-a-machine-learning-classifier/) es una comparación corta y muy legible de varios modelos de clasificación, [Classifier comparison](http://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html) es la visualización de Scikit-Learn de los límites de decisión del clasificador, [Comparing supervised learning algorithms](http://www.dataschool.io/comparing-supervised-learning-algorithms/) es una tabla de comparación de modelos que creé, y [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html) is a more thorough comparison (with links to lots of useful resources).
* [Machine Learning Done Wrong](http://ml.posthaven.com/machine-learning-done-wrong), [Machine Learning Gremlins](https://www.youtube.com/watch?v=tleeC-KlsKA) (31 minutos), [Clever Methods of Overfitting](http://hunch.net/?p=22), and [Common Pitfalls in Machine Learning](http://danielnee.com/?p=155) Todos ofrecen consejos reflexivos sobre cómo evitar errores comunes en el aprendizaje automático.
* [Practical machine learning tricks from the KDD 2011 best industry paper](http://blog.david-andrzejewski.com/machine-learning/practical-machine-learning-tricks-from-the-kdd-2011-best-industry-paper/)y Andrew Ng's [Advice for applying machine learning](http://cs229.stanford.edu/materials/ML-advice.pdf) Incluya consejos un poco más avanzados que los recursos anteriores.
* [An Empirical Comparison of Supervised Learning Algorithms](http://www.cs.cornell.edu/~caruana/ctp/ct.papers/caruana.icml06.pdf) es un trabajo de investigación legible de 2006, que también se presentó como un[talk](http://videolectures.net/solomon_caruana_wslmw/)(77 minutos).

-----

### Clase 22: Presentación final del proyecto
* ¡Presentaciones del proyecto!
* [What's next?](other/advice.md)

-----

## Recursos adicionales

### Datos ordenados
* [Good Data Management Practices for Data Analysis](https://www.prometheusresearch.com/good-data-management-practices-for-data-analysis-tidy-data-part-2/) Resume brevemente los principios de "Datos ordenados".
* [Hadley Wickham's paper](http://www.jstatsoft.org/article/view/v059i10) explica los datos ordenados en detalle e incluye muchos buenos ejemplos.
* Ejemplo de un conjunto de datos ordenado: [Bob Ross](https://github.com/fivethirtyeight/data/blob/master/bob-ross/elements-by-episode.csv)
* Ejemplos de conjuntos de datos desordenados: [NFL ticket prices](https://github.com/fivethirtyeight/data/blob/master/nfl-ticket-prices/2014-average-ticket-price.csv), [airline safety](https://github.com/fivethirtyeight/data/blob/master/airline-safety/airline-safety.csv), [Jets ticket prices](https://github.com/fivethirtyeight/data/blob/master/nfl-ticket-prices/jets-buyer.csv), [Chipotle orders](https://github.com/TheUpshot/chipotle/blob/master/orders.tsv)
* Si sus compañeros de trabajo tienden a crear hojas de cálculo que son [unreadable by computers](https://bosker.wordpress.com/2014/12/05/the-government-statistical-services-terrible-spreadsheet-advice/),pueden beneficiarse de leer estos [tips for releasing data in spreadsheets](http://www.clean-sheet.org/). (Hay algunas sugerencias adicionales en este [answer](http://stats.stackexchange.com/questions/83614/best-practices-for-creating-tidy-data/83711#83711) de cruzado validado.)

### Databases y SQL
* Esta [GA slide deck](https://github.com/justmarkham/DAT5/blob/master/slides/20_sql.pdf) Proporciona una breve introducción a las bases de datos y SQL.The [Python script](https://github.com/justmarkham/DAT5/blob/master/code/20_sql.py) De esa lección demuestra consultas básicas de SQL, así como cómo conectarse a una base de datos SQLite de Python y cómo consultarla usando pandas.
* El repositorio de esto [SQL Bootcamp](https://github.com/brandonmburroughs/sql_bootcamp) Contiene un script SQL extremadamente bien comencionado que es adecuado para caminar por su cuenta.
* Esta [GA notebook](https://github.com/podopie/DAT18NYC/blob/master/classes/17-relational_databases.ipynb) Proporciona una introducción más corta a las bases de datos y SQL que contrasta útilmente las consultas SQL con la sintaxis PANDAS.
* [SQLZOO](http://sqlzoo.net/wiki/SQL_Tutorial), [Mode Analytics](http://sqlschool.modeanalytics.com/), [Khan Academy](https://www.khanacademy.org/computing/computer-programming/sql), [Codecademy](https://www.codecademy.com/courses/learn-sql), [Datamonkey](http://datamonkey.pro/guess_sql/lessons/), and [Code School](http://campus.codeschool.com/courses/try-sql/contents) Todos tienen tutoriales SQL para principiantes en línea que parecen prometedores.Code School también ofrece unn [advanced tutorial](https://www.codeschool.com/courses/the-sequel-to-sql/), aunque no es gratis.
* [w3schools](http://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) Tiene una base de datos de muestra que le permite practicar SQL desde su navegador.Del mismo modo, Kaggle le permite consultar una gran base de datos SQLite de [Reddit Comments](https://www.kaggle.com/c/reddit-comments-may-2015/data) Uso de su aplicación en línea "Scripts".
* [What Every Data Scientist Needs to Know about SQL](http://joshualande.com/data-science-sql/) es una breve serie de publicaciones sobre los conceptos básicos de SQL, y [Introduction to SQL for Data Scientists](http://bensresearch.com/downloads/SQL.pdf) es un artículo con objetivos similares.
* [10 Easy Steps to a Complete Understanding of SQL](https://web.archive.org/web/20150402234726/http://tech.pro/tutorial/1555/10-easy-steps-to-a-complete-understanding-of-sql) es un buen artículo para aquellos que tienen alguna experiencia SQL y quieren entenderlo en un nivel más profundo.
* SArtículo de Qlite en [Query Planning](http://www.sqlite.org/queryplanner.html) Explica cómo las consultas SQL "funcionan".
* [A Comparison Of Relational Database Management Systems](https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems) Da los pros y los contras de SQLite, MySQL y PostgreSQL.
* Si desea profundizar en bases de datos y SQL, Stanford tiene una serie muy respetada de [14 mini-courses](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about).
* [Blaze](http://blaze.pydata.org) es un paquete de Python que le permite usar una sintaxis similar a Pandas para consultar datos que viven en una variedad de sistemas de almacenamiento de datos.

### Sistemas de recomendación
* Esta [GA slide deck](https://github.com/justmarkham/DAT4/blob/master/slides/18_recommendation_engines.pdf) provides a brief introduction to recommendation systems, and the [Python script](https://github.com/justmarkham/DAT4/blob/master/code/18_recommenders_soutions.py) De esa lección demuestra cómo construir un simple recomendador.
*Capítulo 9 de [Mining of Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/bookL.pdf) (36 pages) es una introducción más exhaustiva a los sistemas de recomendación.
* Capítulos 2 a 4 de [A Programmer's Guide to Data Mining](http://guidetodatamining.com/) (165 páginas) proporciona una introducción más amigable, con mucho código y ejercicios de Python.
* El Premio Netflix fue la famosa competencia para mejorar el sistema de recomendaciones de Netflix en un 10%.Aquí hay algunos artículos útiles sobre el premio Netflix:
    * [Netflix Recommendations: Beyond the 5 stars](http://techblog.netflix.com/2012/04/netflix-recommendations-beyond-5-stars.html): Dos publicaciones del blog de Netflix que resume la competencia y su sistema de recomendación
    * [Winning the Netflix Prize: A Summary](http://blog.echen.me/2011/10/24/winning-the-netflix-prize-a-summary/): Descripción general de los modelos y técnicas que entraron en la solución ganadora
    * [A Perspective on the Netflix Prize](http://www2.research.att.com/~volinsky/papers/chance.pdf): Un resumen de la competencia del equipo ganador
* Esta [paper](http://www.cs.umd.edu/~samir/498/Amazon-Recommendations.pdf) resume cómo funciona el sistema de recomendación de Amazon.com, y esto[Stack Overflow Q&A](http://stackoverflow.com/questions/2323768/how-does-the-amazon-recommendation-feature-work)tiene algunos pensamientos adicionales.
* [Facebook](https://code.facebook.com/posts/861999383875667/recommending-items-to-more-than-a-billion-people/) y [Etsy](https://codeascraft.com/2014/11/17/personalized-recommendations-at-etsy/)Tenga publicaciones de blog sobre cómo funcionan sus sistemas de recomendación.
* [The Global Network of Discovery](http://www.gnod.com/) Proporciona algunos recomendadores ordenados para música, autores y películas.
* [The People Inside Your Machine](http://www.npr.org/blogs/money/2015/01/30/382657657/episode-600-the-people-inside-your-machine) (23 minutos) es un episodio de podcast de Money Planet sobre cómo Amazon Mechanical Turks puede ayudar con los motores de recomendación (y el aprendizaje automático en general).
* Coursera tiene un [course](https://www.coursera.org/learn/recommender-systems) En los sistemas de recomendación, si desea profundizar aún más en el material.
