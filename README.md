## Repositorio de curso sobre Data Analytics

Data Analytics (DA) consiste en explorar y analizar grandes cantidades de datos para obtener información sobre el desempeño empresarial pasado con el fin de guiar la planificación empresarial futura. Este curso presenta un conjunto de métodos avanzados centrados en datos que cubren las tres direcciones principales de BA: descriptivo (“¿qué pasó?”), predictivo (“¿qué pasará?”) y prescriptivo (“¿qué debería pasar?”). Los métodos se aplicarán a varios casos de negocios con el objetivo de demostrar cómo extraer valor comercial de los datos, brindar soporte para la toma de decisiones basada en datos junto con principios efectivos de gestión de datos.

**Instructor:** Ulises Gonzalez ([Rizoma](http://www.rizo.ma/), [Linkedin](https://www.linkedin.com/in/ulisesgonzalez/))

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gonzalezulises/101_Data_Analytics_Rizoma.git/HEAD)

|                                                                                  |                                                                           |
| -------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Sesión 1:  [Introducción a Python](#class-1-introduction-to-data-science)        | [Funciones y listas en python](#class-2-command-line-and-version-control) |
| Sesión 2: [Obtención de Datos](#class-3-data-reading-and-cleaning)               | [Iniciación con Pandas](#class-4-exploratory-data-analysis)               |
| Sesión 3: [Análisis exploratorio de Datos I](#class-6-machine-learning)          | [Análisis exploratorio de Datos II](#class-6-machine-learning)            |
| Sesión 4: [Visualización de Datos I](#class-7-getting-data)                      | [Visualización de Datos II](#class-8-k-nearest-neighbors)                 |
| Sesión 5: [Evaluación de modelos de pronóstico](#class-9-basic-model-evaluation) | [Linear Regression](#class-10-linear-regression)                          |
| Sesión 6: [Logistic Regression](#class-11-first-project-presentation)            | [Árboles de decisión](#class-12-logistic-regression)                      |
| Sesión 7: [Clustering](#class-13-advanced-model-evaluation)                      | [Evaluación de modelos](#class-14-naive-bayes-and-text-data)              |
| Sesión 8: [Uso de Tableau](#class-14-naive-bayes-and-text-data)                  | [Publicación de tableros](#class-15-natural-language-processing)          |

### Antes de que comience el curso

* Puedes dar una mirada al [data analyst roadmap](https://roadmap.sh/data-analyst)
* Para usar [google colaboratory](https://colab.research.google.com/)requerirás un correo de gmail para acceder. Si no dispones de uno lo puedes crear [sin costo aca](https://workspace.google.com/)
* Para usar Anaconda no necesitarás algo adicional ya que es cloud, puedes crear una [cuenta acá](https://anaconda.cloud/)
* Podrás usar también el notebook de Kaggle, puedes [crear una cuenta acá](https://www.kaggle.com/#)
* Practique Python utilizando los recursos a continuación.

### Recursos adicionales de práctica

* [Codecademy's Python course](http://www.codecademy.com/en/tracks/python): Buen material para principiantes, incluidos toneladas de ejercicios en el navegador.
* [Dataquest](https://www.dataquest.io): Utiliza ejercicios interactivos para enseñar a Python en el contexto de la ciencia de datos.
* [Google's Python Class](https://developers.google.com/edu/python/): Un poco más avanzado, incluidas horas de videos útiles de conferencias y ejercicios descargables (con soluciones).
* [Introduction to Python](http://introtopython.org/): Una serie de cuadernos de iPython que hacen un gran trabajo explicando conceptos y estructuras de datos de Core Python.
* [Python for Informatics](http://www.pythonlearn.com/book.php): Un libro muy orientado a principiante, con asociado [slides](https://drive.google.com/folderview?id=0B7X1ycQalUnyal9yeUx3VW81VDg&usp=sharing) and [videos](https://www.youtube.com/playlist?list=PLlRFEj9H3Oj4JXIwMwN1_ss1Tk8wZShEJ).
* [A Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182): Lea la sección de descripción general para una introducción muy rápida a Python.
* [Beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) Código de taller: útil para revisión y referencia.
* [Python Tutor](http://pythontutor.com/): Le permite visualizar la ejecución del código Python.

-----

<a target="_blank" href="https://anaconda.cloud/api/nbserve/launch_notebook?nb_url=https%3A%2F%2Fanaconda.cloud%2Fapi%2Fprojects%2F26bdf97e-88f5-4cb9-b9fa-5b222176f941%2Ffiles%2F01_Introduccio%CC%81n_Python_Aprendizaje.ipynb%3Fversion%3Dfd2ebbdb-2222-4d4c-a1d3-27db0ae408f2">
    <img src="https://static.anaconda.cloud/content/a22d04e8445b700f28937ab3231b8cded505d0395c63b7a269696722196d5415" alt="Lanzar notebook sesión 1"/>
</a>

### Sesión 1: Introducción a Data Analytics

* Bienvenida a la formación
* Resumen del curso([slides](slides/01_course_overview.pdf))
* Introducción a Data Analytics ([slides](slides/01_intro_to_data_analytics.pdf))
* Discuta el proyecto del curso: [requerimientos](project/README.md) and [proyectos de ejemplo](https://github.com/justmarkham/DAT-project-examples)
* Tipos de datos([slides](slides/01_types_of_data.pdf)) and [fuentes de datos publicos](project/public_data.md)

**Asignación:**

* Leer Introducción a la programación y al análisis de datos con Python
* Leer la ruta de [Data analytics](https://roadmap.sh/data-analyst)
* Desarrollar el 01 Laboratorio de la Sesión 1 (Asignación)
* (Opcional) [Aprende Git y GitHub - Curso desde Cero](https://www.youtube.com/watch?v=mBYSUUnMt9M), o leer las secciones 1.1 a 2.2 de [Pro Git](https://git-scm.com/book/es/v2).

**Recursos:**
*Para una mirada útil a los diferentes tipos de científicos de datos, lea [analizar los analizadores] (<https://www.datascienceassn.org/sites/default/files/Analyzing_the_Analyzers.pdf>) (40 páginas).

* Para algunas ideas sobre lo que es ser un científico de datos, lea estas publicaciones breves de [Win-vector] (<http://www.win-vector.com/blog/2012/09/on-being-a-data-Scientist/>) y [DataScope Analytics] (<http://datascopeopealytics.com/what-we-think/2014/07/31/six-qualities-of-a-great-data-scientist>).
* Quora tiene una [FAQ de tema de ciencias de datos] (<https://www.quora.com/data-science>) con muchas preguntas y respuestas interesantes.
* Sobre la minería de datos (<https://aws.amazon.com/es/what-is/data-mining/>)

-----

**Recursos Adicionales: (Opcional)**

* Si deseas continuar aprendiendo python, puedes utilizar los siguientes recursos disponibles:
  * [Introduction to Python](http://introtopython.org/)hace un gran trabajo explicando Python Essentials e incluye toneladas de código de ejemplo.
  * Si te gusta aprender de un libro, [Python for Informatics](http://www.pythonlearn.com/html-270/) Tiene capítulos útiles sobre cadenas, listas y diccionarios.
  * Si prefiere ejercicios interactivos, pruebe estas lecciones de [Codecademy](http://www.codecademy.com/en/tracks/python): "Python listas y diccionarios" y "un día en el supermercado".
  * Si tiene más tiempo, pruebe las misiones 2 y 3 de [DataQuest's Learning Python](https://www.dataquest.io/course/learning-python) curso.
  * Si ya ha dominado estos temas y quiere más desafío, intente resolver [Python Challenge](http://www.pythonchallenge.com/) Número 1 (decodificando un mensaje)
* Para darle un marco para pensar en su proyecto, mire [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk) (10 minutes). (Este es el [IPython notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/01_machine_learning_intro.ipynb) shown en el video.) Alternativamente, lea [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/), que se centra en un modelo de aprendizaje automático específico llamado árboles de decisión.
* [Want to understand Python's comprehensions? Think in Excel or SQL](http://blog.lerner.co.il/want-to-understand-pythons-comprehensions-think-like-an-accountant/) Puede ser útil si todavía está confundido por las comprensiones de la lista.
* [My code isn't working](http://www.tecoed.co.uk/uploads/1/4/2/4/14249012/624506_orig.png) es un gran diagrama de flujo que explica cómo depurar los errores de Python.
* [PEP 8](https://www.python.org/dev/peps/pep-0008/) es la guía de estilo "clásica" de Python, y vale la pena leer si desea escribir un código legible que sea consistente con el resto de la comunidad de Python.
* Si quieres entender a Python en un nivel más profundo, Ned Batchelder's [Loop Like A Native](http://nedbatchelder.com/text/iter.html)y [Python Names and Values](http://nedbatchelder.com/text/names1.html)son excelentes presentaciones.

-----
**¿Quieres ir más allá de lo aprendido?**

Podrías aprender  Git y Markdown que son herramientas valiosas para la analítica de datos por varias razones como:

**Git**

* **Control de Versiones:** Git permite gestionar cambios en el código y los datos a lo largo del tiempo. Esto es esencial en proyectos de análisis de datos, donde se realizan múltiples iteraciones y ajustes en los scripts y datasets.
* **Colaboración:** Git facilita la colaboración entre equipos, permitiendo que múltiples analistas trabajen en el mismo proyecto sin conflictos. Cada miembro puede hacer cambios en su propia rama y luego fusionar los resultados.
* **Rastreo de Historial:** Con Git, puedes rastrear quién hizo qué cambios y cuándo. Esto es crucial para auditar y entender cómo y por qué evolucionó un análisis específico.
* **Gestión de Proyectos:** Git integra herramientas para gestionar proyectos de datos, como issues y pull requests, que ayudan a organizar y revisar el trabajo.

**Markdown**

* **Documentación Clara:** Markdown permite crear documentación clara y estructurada, que es fácil de leer y escribir. Documentar el código y los análisis es fundamental para asegurar que los resultados sean reproducibles y comprensibles.
* **Reportes Dinámicos:** Herramientas como Jupyter Notebooks utilizan Markdown para combinar texto, código y visualizaciones en un solo documento. Esto facilita la creación de reportes dinámicos que muestran tanto el proceso como los resultados del análisis.
* **Compatibilidad y Portabilidad:** Markdown es un formato ligero y ampliamente compatible que puede ser convertido a varios formatos (HTML, PDF, etc.), lo que facilita compartir y publicar resultados.

**Integración Práctica**

* **Jupyter Notebooks:** En estos entornos, el conocimiento de Git y Markdown es crucial para manejar notebooks y colaborar eficientemente. Git gestiona el versionado y la colaboración, mientras que Markdown documenta y explica los análisis.
* **Proyectos Reproducibles:** Con Git para el control de versiones y Markdown para la documentación, los proyectos de analítica de datos se vuelven más reproducibles y fáciles de entender para otros analistas o stakeholders.
* **Comunicación de Resultados:** Markdown ayuda a comunicar los resultados de forma clara y visualmente atractiva, lo cual es esencial para presentar hallazgos a equipos no técnicos o directivos.

**Recursos Git y Markdown:**

* [Pro Git](http://git-scm.com/book/en/v2) es un excelente libro para aprender Git lea los dos primeros capítulos para obtener una comprensión más profunda del control de versiones y los comando básicos.
* Si quieres practicar mucho Git y aprender muchos más comandos), [Git Immersion](http://gitimmersion.com/)
* Si quieres entender cómo contribuir en GitHub, primero tienes que entender [forks and pull requests](http://www.dataschool.io/simple-guide-to-forks-in-github-and-git/).
* [GitRef](http://gitref.org/) es mi guía de referencia favorita para los comandos Git, y [Git quick reference for beginners](http://www.dataschool.io/git-quick-reference-for-beginners/) es una guía más corta con comandos agrupados por flujo de trabajo
* [Cracking the Code to GitHub's Growth](https://growthhackers.com/growth-studies/github) explicaPorQuéGithubEsTanPopularEntreLosDesarrolladores
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) proporcionaUnConjuntoExhaustivoDeEjemplosDeMarkdownConExplicacionesConcisasGithub's[Mastering Markdown](https://guides.github.com/features/mastering-markdown/)esUnaGuíaMásSimpleYAtractiva,PeroEsMenosIntegral

**Recursos de línea de comandos:**

* Si quieres profundizar mucho en la línea de comando, [Data Science at the Command Line](http://shop.oreilly.com/product/0636920032823.do) es un gran libro.El [companion website](http://datascienceatthecommandline.com/) Proporciona instrucciones de instalación para una "caja de herramientas de ciencia de datos" (una máquina virtual con muchas más herramientas de línea de comandos), así como una larga guía de referencia para las herramientas de línea de comandos populares.
* Si desea hacer más en la línea de comando con archivos CSV, pruebe [csvkit](http://csvkit.readthedocs.org/), que se puede instalar a través de `pip`.

-----

### Sesión 2: Obtención de datos e iniciación con Pandas

* Obtención de datos ([slides](slides/01_intro_to_data_analytics.pdf))
* Iniciación con Pandas (slides)

**Asignación:**

* Leer Getting started with pandas
* Leer la documentación de [pandas](https://pandas.pydata.org/docs/)
* Desarrollar el 02_Laboratorio de la Sesión 2 (Asignación)

**Recursos:**

* [Want to understand Python's comprehensions? Think in Excel or SQL](http://blog.lerner.co.il/want-to-understand-pythons-comprehensions-think-like-an-accountant/) Puede ser útil si todavía está confundido por las comprensiones de la lista.
* [My code isn't working](http://www.tecoed.co.uk/uploads/1/4/2/4/14249012/624506_orig.png) es un gran diagrama de flujo que explica cómo depurar los errores de Python.
* [PEP 8](https://www.python.org/dev/peps/pep-0008/) es la guía de estilo "clásica" de Python, y vale la pena leer si desea escribir un código legible que sea consistente con el resto de la comunidad de Python.
* Si quieres entender a Python en un nivel más profundo, Ned Batchelder's [Loop Like A Native](http://nedbatchelder.com/text/iter.html)y [Python Names and Values](http://nedbatchelder.com/text/names1.html)son excelentes presentaciones.
* Pandas ([code](code/04_pandas.py)):
  * MOVIELENS 100K Clasificaciones de películas ([data](data/u.user), [data dictionary](http://files.grouplens.org/datasets/movielens/ml-100k-README.txt), [website](http://grouplens.org/datasets/movielens/))
  * Consumo de alcohol por país ([data](data/drinks.csv), [article](http://fivethirtyeight.com/datalab/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/))
  * Informes de avistamientos de ovnis([data](data/ufo.csv), [website](http://www.nuforc.org/webreports.html))
* Ejercicio de preguntas del proyecto

**Recursos adicionales**:

* Browsing or searching the Pandas [API Reference](http://pandas.pydata.org/pandas-docs/stable/api.html) es una excelente manera de localizar una función incluso si no sabe su nombre exacto.
* [What I do when I get a new data set as told through tweets](http://simplystatistics.org/2014/06/13/what-i-do-when-i-get-a-new-data-set-as-told-through-tweets/) es una mirada divertida (pero esclarecedora) al proceso de análisis de datos exploratorios.

- Recursos API: Este guión de Python para [query the U.S. Census API](https://github.com/laurakurup/census-api) fue creado por un ex alumno de DA.Es un poco más complicado que el ejemplo que usamos en la clase, está muy bien comentado y puede proporcionar un marco útil para escribir su propio código para consultar las API.

* [Mashape](https://www.mashape.com/explore) y [Apigee](https://apigee.com/providers)Permitirle explorar toneladas de diferentes API.Alternativamente, un [Python API wrapper](http://www.pythonforbeginners.com/api/list-of-python-apis) está disponible para muchas API populares.
* the [Data Science Toolkit](http://www.datasciencetoolkit.org/) es una colección de API basadas en la ubicación y relacionadas con el texto.
* [API Integration in Python](https://realpython.com/blog/python/api-integration-in-python/) Proporciona una introducción muy legible a las API REST.
* Microsoft's [Face Detection API](https://www.projectoxford.ai/demo/face#detection), que poderes[How-Old.net](http://how-old.net/), es un gran ejemplo de cómo se puede aprovechar una API de aprendizaje automático para producir una aplicación web convincente.

-----
**¿Quieres ir más allá de lo aprendido?

**Pandas AI** es una **mejora** de la librería de [Pandas](https://pandas.pydata.org/), que ha sido **combinada con la tecnología de OpenAI**, con el resultado de pode **ahorrarnos tiempo** en tener que seleccionar los encabezados, franjas y demás. Además de eso, también puede hacer cosas que le pidamos, en relación a los **csv** o dataframes, que le indiquemos.
Puedes obtener información si deseas llevar al siguiente nivel:
* [Introducción a PandasAI](https://docs.pandas-ai.com/intro)

-----

### Sesión 3: Combinación de datos y Análisis de datos exploratorios ###

* Análisis de datos exploratorios (slides)
* Parte 2 del análisis de datos exploratorios con pandas([code](code/04_pandas.py))

**Asignación:**

* Leer Preparing Data for EDA
* [Paso a paso de un análisis exploratorio de datos](https://docs.google.com/document/d/10O7nB5zUSjJFKwH_cw_sCi7VPAP2jOaw1_6E05DC4RY/edit?usp=sharing)
* Desarrollar el 03_Laboratorio de la Sesión 3 (Asignación)
* (opcional) Puedes desarrollar el ejercicio Pandas ([code](code/04_pandas.py)):
  * MOVIELENS 100K Clasificaciones de películas ([data](data/u.user), [data dictionary](http://files.grouplens.org/datasets/movielens/ml-100k-README.txt), [website](http://grouplens.org/datasets/movielens/))
  * Consumo de alcohol por país ([data](data/drinks.csv), [article](http://fivethirtyeight.com/datalab/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/))
* Ejercicio de preguntas del proyecto
* Leer [How Software in Half of NYC Cabs Generates $5.2 Million a Year in Extra Tips](http://iquantny.tumblr.com/post/107245431809/how-software-in-half-of-nyc-cabs-generates-5-2) Para un excelente ejemplo de análisis de datos exploratorios.
* Leer [Anscombe's Quartet, and Why Summary Statistics Don't Tell the Whole Story](http://data.heapanalytics.com/anscombes-quartet-and-why-summary-statistics-dont-tell-the-whole-story/) Para un ejemplo clásico de por qué la visualización es útil.

**Recursos:**

* Para obtener más pandas, lea esto [three-part tutorial](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/), O revise estos dos cuadernos excelentes (pero  largos) en Pandas: [introduction](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_5-Introduction-to-Pandas.ipynb) and [data wrangling](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_6-Data-Wrangling-with-Pandas.ipynb).
* Si quieres profundizar en los pandas (y numpy), lee el libro [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do),Escrito por el Creador de Pandas.
* Este cuaderno demuestra los diferentes tipos de [joins in Pandas](notebooks/05_pandas_merge.ipynb), para cuando necesite descubrir cómo fusionar dos marcos de datos.
* Este es un buen tutorial breve sobre [pivot tables](https://beta.oreilly.com/learning/pivot-tables) en pandas.

**Recursos adicionales:

* Para trabajar con datos geoespaciales en Python, [GeoPandas](http://geopandas.org/index.html) parece prometedor.Este [tutorial](http://michelleful.github.io/code-blog/2015/04/24/sgmap/) Utiliza Geopandas (y Scikit-Learn) para construir un "mapa callejero lingüístico" de Singapur.
* Browsing or searching the Pandas [API Reference](http://pandas.pydata.org/pandas-docs/stable/api.html) es una excelente manera de localizar una función incluso si no sabe su nombre exacto.
* [What I do when I get a new data set as told through tweets](http://simplystatistics.org/2014/06/13/what-i-do-when-i-get-a-new-data-set-as-told-through-tweets/) es una mirada divertida (pero esclarecedora) al proceso de análisis de datos exploratorios.
* Leer [How Software in Half of NYC Cabs Generates $5.2 Million a Year in Extra Tips](http://iquantny.tumblr.com/post/107245431809/how-software-in-half-of-nyc-cabs-generates-5-2) Para un excelente ejemplo de análisis de datos exploratorios.

-----

### Clase 4: Visualización de Datos

* Tarea de Python con los datos de Chipotle adeudados ([solution](code/03_python_homework_chipotle.py), [detailed explanation](notebooks/03_python_homework_chipotle_explained.ipynb))
* Visualización con pandas y matplotlib ([notebook](notebooks/05_pandas_visualization.ipynb))

**Asignación:**
* Leer Data Manipulation and visualization in python
* Desarrollar el 05_Laboratorio_de_Visualización (Asignación)
* Obtén inspiración [desde esta galería](https://www.data-to-viz.com/)

**Recursos:**

* Mirar [Look at Your Data](https://www.youtube.com/watch?v=coNDCIMH8bk) (18 minutos) Para un excelente ejemplo de por qué la visualización es útil para comprender sus datos.
* Dispones de más detalles de visualización en este  [notebook](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_7-Plotting-with-Pandas.ipynb) o el [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) De la documentación oficial de Pandas.
* Para aprender a personalizar aún más sus lienzos, navegue por este [notebook on matplotlib](https://github.com/fonnesbeck/Bios8366/blob/master/notebooks/Section2_4-Matplotlib.ipynb) o este [similar notebook](https://github.com/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb).
* Leer [Overview of Python Visualization Tools](http://pbpython.com/visualization-tools-1.html) Para una comparación útil de matplotlib, pandas, seaborn, ggplot, bokeh, pygal y tramly.
* Para explorar diferentes tipos de visualizaciones y cuándo usarlas, [Choosing a Good Chart](http://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf) y [The Graphic Continuum](https://gijn.org/resource/document-of-the-day-visual-vocabulary/) son buenas referencias de una página y el interactivo [R Graph Catalog](http://shiny.stat.ubc.ca/r-graph-catalog/) tiene prácticas capacidades de filtrado.
* [Harvard's Data Science course](http://cs109.github.io/2014/) Incluye una excelente conferencia sobre[Visualization Goals, Data Types, and Statistical Graphs](http://cm.dce.harvard.edu/2015/01/14328/L03/screen_H264LargeTalkingHead-16x9.shtml) (83 minutos), para el cual el [slides](https://docs.google.com/file/d/0B7IVstmtIvlHLTdTbXdEVENoRzQ/edit) también están disponibles.
* Leer [Anscombe's Quartet, and Why Summary Statistics Don't Tell the Whole Story](http://data.heapanalytics.com/anscombes-quartet-and-why-summary-statistics-dont-tell-the-whole-story/) Para un ejemplo clásico de por qué la visualización es útil.

-----
**¿Quieres ir más allá de lo aprendido?

En el mundo actual, la capacidad de interpretar y visualizar datos de manera efectiva se ha convertido en una habilidad esencial para profesionales de diversas disciplinas. Scimago Graphica es una aplicación innovadora que ha surgido como una herramienta poderosa para satisfacer esta necesidad. Diseñada para transformar datos complejos en visualizaciones intuitivas y significativas. Aplicaciones como Scimago Graphica, Datawraper o Graphex no sólo facilitan el análisis de datos, sino que también mejoran la comunicación de información crucial.

**¿Qué son estás aplicaciones?**

Son herramientas low-code de visualización de datos avanzada que permite a los usuarios crear gráficos interactivos y dinámicos de manera rápida y sencilla. Con un enfoque en la accesibilidad y la facilidad de uso, esta herramienta está diseñada para ser utilizada por una amplia variedad de profesionales, desde científicos e investigadores hasta analistas de negocios y educadores.

**Motivación para su uso**

1. **Simplicidad y Potencia en un Solo Lugar**: Combinan una interfaz de usuario intuitiva con capacidades robustas de análisis y visualización. No se requiere ser un experto en programación o en software de análisis de datos para comenzar a crear visualizaciones impactantes.

2. **Interactividad y Dinamismo**: Las visualizaciones creadas son interactivas, lo que permite a los usuarios explorar los datos en profundidad y descubrir patrones y tendencias ocultas. Esta característica es especialmente valiosa para presentaciones y reportes, donde la claridad y la capacidad de respuesta son cruciales.

3. **Colaboración Efectiva**: En un entorno cada vez más colaborativo, permiten compartir fácilmente visualizaciones y proyectos con colegas y equipos, facilitando la colaboración y la toma de decisiones basada en datos.

4. **Aplicaciones Multidisciplinarias**: Desde la investigación académica hasta el análisis de mercado, pasando por la educación y la gestión de proyectos, Son herramientas versátiles que pueden adaptarse a las necesidades de diversos campos. Esto las convierte en una inversión valiosa para cualquier profesional que trabaje con datos.

5. **Acceso a Recursos y Soporte**: ofrecen una variedad de recursos, incluyendo tutoriales y soporte técnico, para ayudar a los usuarios a maximizar su experiencia y aprovechar al máximo las capacidades de la herramienta.

**Herramientas:
* [Scimago Graphica](https://www.graphica.app/)
* [Datawrapper](https://www.datawrapper.de/)
* [Graphext](https://www.graphext.com/)

-----

### Clase 5: Evaluación de modelos de pronósticos y regresión lineal ###

*Ejercicio de "aprendizaje humano":
    * [Iris dataset](http://archive.ics.uci.edu/ml/datasets/Iris) Organizado por el repositorio de aprendizaje automático de UCI
    *[Iris photo](http://sebastianraschka.com/Images/2014_python_lda/iris_petal_sepal.png)
    * [Notebook](notebooks/06_human_learning_iris.ipynb)

* Introducción al aprendizaje automático ([slides](slides/06_machine_learning.pdf))
* Ejercicio de aprendizaje automático([article](http://blog.dominodatalab.com/10-interesting-uses-of-data-science/))
* Regresión lineal ([notebook](notebooks/10_linear_regression.ipynb))
  * [Capital Bikeshare dataset](data/bikeshare.csv) used in a Kaggle competition
  * [Data dictionary](https://www.kaggle.com/c/bike-sharing-demand/data)
* Ejemplo de ingeniería de características: [Predicting User Engagement in Corporate Collaboration Network](https://github.com/mikeyea/DAT7_project/blob/master/final%20project/Class_Presention_MYea.ipynb)

**Asignación:**
* Leer Data Manipulation and visualization in python
* Desarrollar el 05_Laboratorio_de_Visualización (Asignación)
* Obtén inspiración [desde esta galería](https://www.data-to-viz.com/)

**Recursos de aprendizaje automático:**

* Para un resumen muy rápido de los puntos clave sobre el aprendizaje automático, mire [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk) (10 minutos) o leer el [associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/01_machine_learning_intro.ipynb).
* Para una introducción más profunda al aprendizaje automático, lea la Sección 2.1 (14 páginas) del excelente libro de Hastie y Tibshirani, [An Introduction to Statistical Learning](https://www.stat.berkeley.edu/users/rabbee/s154/ISLR_First_Printing.pdf). (¡Es una descarga gratuita de PDF!)
* *La [Learning Paradigms](http://work.caltech.edu/library/014.html) Video (13 minutos) de [Caltech's Learning From Data course](http://work.caltech.edu/telecourse.html) Proporciona una buena comparación del aprendizaje supervisado versus no supervisado, así como una introducción al "aprendizaje de refuerzo".
* [Real-World Active Learning](https://beta.oreilly.com/ideas/real-world-active-learning) es una introducción legible y exhaustiva al "aprendizaje activo", una variación del aprendizaje automático en la que los humanos etiquetan solo las observaciones más "importantes".
* Para obtener una vista previa de parte del contenido de aprendizaje automático que cubriremos durante el curso, lea Sebastian Raschka's [overview of the supervised learning process](https://github.com/rasbt/pattern_classification/blob/master/machine_learning/supervised_intro/introduction_to_supervised_machine_learning.md).
* [Data Science, Machine Learning, and Statistics: What is in a Name?](http://www.win-vector.com/blog/2013/04/data-science-machine-learning-and-statistics-what-is-in-a-name/) Discute las diferencias entre estos (y otros) términos.
* [The Emoji Translation Project](https://www.kickstarter.com/projects/fred/the-emoji-translation-project)es una aplicación realmente divertida del aprendizaje automático.
* Busque el[characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/), y luego lee sobre el [67 distinct segments](http://doc.arcgis.com/en/esri-demographics/data/tapestry-segmentation.htm) en detalle.

**Recursos de cuaderno de iPython**

* Para un resumen de la introducción del cuaderno de iPython (y una vista previa de Scikit-Learn), mire [scikit-learn and the IPython Notebook](https://www.youtube.com/watch?v=IsXXlYVBt1M) (15 minutos) o leer el[associated notebook](https://github.com/justmarkham/scikit-learn-videos/blob/master/02_machine_learning_setup.ipynb).
*Si desea aprender el cuaderno de iPython, el oficial [Notebook tutorials](https://github.com/jupyter/notebook/blob/master/docs/source/examples/Notebook/Examples%20and%20Tutorials%20Index.ipynb) Son útiles.
*Esta [Reddit discussion](https://www.reddit.com/r/Python/comments/3be5z2/do_you_prefer_ipython_notebook_over_ipython/) Compara las fortalezas relativas del cuaderno de Ipython y Spyder.

* Ejercicio de aprendizaje automático([article](http://blog.dominodatalab.com/10-interesting-uses-of-data-science/))
* Regresión lineal ([notebook](notebooks/10_linear_regression.ipynb))
  * [Capital Bikeshare dataset](data/bikeshare.csv) used in a Kaggle competition
  * [Data dictionary](https://www.kaggle.com/c/bike-sharing-demand/data)
* Ejemplo de ingeniería de características: [Predicting User Engagement in Corporate Collaboration Network](https://github.com/mikeyea/DAT7_project/blob/master/final%20project/Class_Presention_MYea.ipynb)

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
* Sección 3.3.1 de [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (4 pages)Tiene una gran explicación de la codificación ficticia para características categóricas.

-----

### Clase 6: Regresión logística y árboles de decisión ###

* Yelp Votes Tarea Due ([Solución] (cuadernos/10_yelp_votes_homework.ipynb))
* Regresión logística ([cuaderno] (cuadernos/12_logistic_regression.ipynb))
* [Conjunto de datos de identificación de vidrio] (<https://archive.ics.uci.edu/ml/datasets/glass+identification>)
* Ejercicio con Titanic Data ([cuaderno] (cuaderno/12_titanic_confusion.ipynb), [data] (data/titanic.csv), [Data Dictionary] (<https://www.kaggle.com/c/titanic/data>)))
* Confusion Matrix ([diapositivas] (diapositivas/12_confusion_matrix.pdf), [cuaderno] (cuaderno/12_titanic_confusion.ipynb)))

**Tarea:**

* Si aún no se siente cómodo con toda la terminología de la matriz de confusión, mire los videos de Rahul Patwari en [Sensibilidad y especificidad intuitiva] (<https://www.youtube.com/watch?v=U4_3fditnwg>) (9 minutos) y [[9 minutos) y [[9 minutos) y [[La compensación entre sensibilidad y especificidad] (https://www.youtube.com/watch?v=vtydyggeqyo) (13 minutos).
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

### Clase 7: Clustering y Evaluación de modelos ###

* Breve revisión de pandas ([cuaderno] (cuadernos/08_pandas_review.ipynb)))
* K-Near más vecinos y scikit-learn ([cuaderno] (cuadernos/08_knn_sklearn.ipynb))
* Ejercicio con los datos del jugador de la NBA ([cuaderno] (cuaderno/08_nba_knn.ipynb), [data] (<https://github.com/justmarkham/dat4-students/blob/master/kerry/final/nba_players_2015.csv>), [Dicción de datos] (<https://github.com/justmarkham/dat-project-examples/blob/master/pdf/nba_paper.pdf>)))
* Explorando la compensación de varianza de sesgo ([cuaderno] (cuadernos/08_bias_variance.ipynb))

**Tarea:**

* Asignación de lectura en la [compensación de varianza de sesgo] (tarea/09_bias_variance.md)
* Lea la [Introducción a la reproducibilidad] de Kevin (<http://www.dataschool.io/reproducibilidad-is-not-just-for-researchers/>), lea la guía de Jeff Leek para crear un análisis reproducible] (https: // github.com/jtleek/dataHaring), y vea este video relacionado [Video de Informe de Colbert] (<http://thecolberstreport.cc.com/videos/dcyvro/austerity-s-sepersheet-error>) (8 minutos).
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

Evaluación básica del modelo

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

### Clase 8: Introducción a Tableau ###

-----

### Revisión del curso y recursos adicionales ###

* [Evaluación del curso de Data Analytics](https://tally.so/r/wkZ62o)

**Recursos:**

* ScikitLearn's [machine learning map](http://scikit-learn.org/stable/tutorial/machine_learning_map/) Puede ayudarlo a elegir el "mejor" modelo para su tarea.
* [Choosing a Machine Learning Classifier](http://blog.echen.me/2011/04/27/choosing-a-machine-learning-classifier/) es una comparación corta y muy legible de varios modelos de clasificación, [Classifier comparison](http://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html) es la visualización de Scikit-Learn de los límites de decisión del clasificador, [Comparing supervised learning algorithms](http://www.dataschool.io/comparing-supervised-learning-algorithms/) es una tabla de comparación de modelos que creé, y [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html) is a more thorough comparison (with links to lots of useful resources).
* [Machine Learning Done Wrong](http://ml.posthaven.com/machine-learning-done-wrong), [Machine Learning Gremlins](https://www.youtube.com/watch?v=tleeC-KlsKA) (31 minutos), [Clever Methods of Overfitting](http://hunch.net/?p=22), and [Common Pitfalls in Machine Learning](http://danielnee.com/?p=155) Todos ofrecen consejos reflexivos sobre cómo evitar errores comunes en el aprendizaje automático.
* [Practical machine learning tricks from the KDD 2011 best industry paper](http://blog.david-andrzejewski.com/machine-learning/practical-machine-learning-tricks-from-the-kdd-2011-best-industry-paper/)y Andrew Ng's [Advice for applying machine learning](http://cs229.stanford.edu/materials/ML-advice.pdf) Incluya consejos un poco más avanzados que los recursos anteriores.
* [An Empirical Comparison of Supervised Learning Algorithms](http://www.cs.cornell.edu/~caruana/ctp/ct.papers/caruana.icml06.pdf) es un trabajo de investigación legible de 2006, que también se presentó como un[talk](http://videolectures.net/solomon_caruana_wslmw/)(77 minutos).

-----

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

### Evaluación avanzadas de modelos

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

### Regularización y expresiones regulares ###

* Regularización ([notebook](notebooks/20_regularization.ipynb))
  * Regresión: [Ridge](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html), [RidgeCV](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeCV.html), [Lasso](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html), [LassoCV](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LassoCV.html)
  * Clasificación: [LogisticRegression](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
  * Funciones de ayudante: [Pipeline](http://scikit-learn.org/stable/modules/pipeline.html), [GridSearchCV](http://scikit-learn.org/stable/modules/grid_search.html)
* Expresiones regulares
  * [Baltimore homicide data](data/homicides.txt)
  * [Regular expressions 101](https://regex101.com/#python): real-time testing of regular expressions
  * [Reference guide](code/20_regex_reference.py)
  * [Exercise](code/20_regex_exercise.py)

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

### Scikit-learn y Clustering avanzado

* Advanced scikit-learn ([notebook](notebooks/19_advanced_sklearn.ipynb))
  * [StandardScaler](http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html): standardizing features
  * [Pipeline](http://scikit-learn.org/stable/modules/pipeline.html): chaining steps
* Clustering ([slides](slides/19_clustering.pdf), [notebook](notebooks/19_clustering.ipynb))
  * K-means: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html), [visualization 1](http://tech.nitoyon.com/en/blog/2013/11/07/k-means/), [visualization 2](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
  * DBSCAN: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html), [visualization](http://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)

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
* La [K-modes algorithm](http://www.cs.ust.hk/~qyang/Teaching/537/Papers/huang98extensions.pdf) Se puede utilizar para agrupar conjuntos de datos de características categóricas sin convertirlos en valores numéricos.Aquí hay una [implementación de Python] (<https://github.com/nicodv/kmodes>).
* Aquí hay algunos ejemplos divertidos de agrupación: [A Statistical Analysis of the Work of Bob Ross](http://fivethirtyeight.com/features/a-statistical-analysis-of-the-work-of-bob-ross/) (with [data and Python code](https://github.com/fivethirtyeight/data/tree/master/bob-ross)), [How a Math Genius Hacked OkCupid to Find True Love](http://www.wired.com/2014/01/how-to-hack-okcupid/all/), and [characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/).
