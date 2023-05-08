<img src="https://github.com/jzavalar/2211088-informatica/blob/main/conjunto-baseIzt.png" alt="UAM Iztapalapa" width="60%"/>

## Programa Analítico de la UEA Análisis de Decisiones (Teoría y Práctica)
## Licenciatura en Administración

**Clave de la UEA:** *2211092*, **Grupo:** *HE51*, **Trimestre:** *23-I*

**Horario:** *Lunes y miércoles* de *14:00 a 16:00*.

**Salón:** Anexo A, Sala J (AA-J).

**Asesorías:**  *Martes* de *20:00* a *22:00 hr*, vía [Telegram](https://telegram.org/apps), previa solicitud.

**Profesor:** *dr. Jesús Zavala Ruiz*

**Contacte al profesor**:
- Correo electrónico: [jzr@xanum.uam.mx](mailto:jzr@xanum.uam.mx)
- Telegram: <img src="https://github.com/jzavalar/2211088-informatica/blob/main/telegram_logo.svg" alt="Telegram" width="3%"/> [@jzavalar](https://telegram.me/jzavalar)


### Introducción

Afines de los años 1930s, a solicitud del gobierno británico, el profesor P.M.S. Blackett y su equipo de científicos e ingenieros desarrollaron métodos para "resolver problemas técnicos relacionados con el desarrollo de nuevas armas y equipo durante la Segunda Guerra Mundial" (Jaiswal, 1997, p. 2)[^1], con un enfoque hacia problemas técnicos operativos (p. 4). Según, este autor, después de la Segunda Guerra Mundial, los científicos e ingenieros asociados con el profesor Blackett pasaron de la industria militar a los sectores civiles como el transporte, la salud y la industria, convencidos de que podían analizar esas operaciones con las mismas herramientas analíticas (p. 4).   

Así surgió la **investigación de operaciones** (*operations research*) que se concibió como una "colección de herramientas y técnicas que podían utilizarse para mejorar sistemas bajo el control de un encargado independientemente de su campo de la actividad" (idem). El arsenal metodológico y computacional de la posguerra incluyó la *programación lineal*, la *teoría de juegos*, la *programación dinámica*, la *simulación de eventos discretos* con la computadora digital, adicionalmente a las *teorías de inventarios y colas*, el *modelado de Markov* y los métodos básicos de *optimización*. Actualmente, la *investigación de operaciones* se define como "la aplicación de los métodos de la ciencia a problemas complejos que se presentan en la dirección y la administración de grandes sistemas de hombres, máquinas, materiales y dinero, en la industria, los negocios, el gobierno y la defensa" (Gass y Fu, 2013, p. viii)[^2]; aunque también se define como "la ciencia de decidir cómo obtener el mejor diseño y cómo operar los sistemas hombre-máquina" y como "un método científico para proveer de los departamentos ejecutivos una base cuantitativa para la toma de decisiones" (idem).  

La investigación de operaciones derivó en el '*análisis de sistemas*' asociado a la *toma de decisiones*, considerada para entonces como "el examen sistemático de las distintas alternativas" (Hitch, 1955, p. 477)[^3] que se atribuyó como competencia de los gerentes (*managers*). En cambio, el llamado '*análisis puro*' estaba relacionado con la logística operativa y era realizado por los 'técnicos' (*technicians*) o 'analistas' (*analysts*). Así, el *análisis de sistemas* se puede considerar como "un enfoque sistemático para ayudar a un tomador de decisiones (*decision maker*) que elija un curso de acción, investigando un problema completo, buscando objetivos y alternativas y comparándolas considerando sus consecuencias, usando un marco de referencia apropiado —tan analítico como sea posible— para invocar el juicio y la intuición de expertos sobre el problema" (Jaiswal, 1997, p. 5). Esta definición sugiere que un '*ciclo de toma de decisiones*' consiste desde "la definición de los objetivos, la exploración de las alternativas y su evaluación en términos de sus costos(/beneficios) y eficacia" (idem).  

Desde los años 1950s, el concepto de *análisis de sistemas* ha permanecido, hasta nuestros días, asociado a la 'toma de decisiones', a la 'administración de proyectos' y otras disciplinas, siempre persiguiendo el mismo objetivo: *decidir racionalmente ante la incertidumbre*. Como consecuencia, surgieron las *ciencias de la administración* como un enfoque interdisciplinario que pasó de la eficiencia técnica a la eficacia de los sistemas sociotécnicos. Formalmente, la *ciencia de la administración* (*management science*) se define como la "aplicación de la metodología o los principios científicos a las decisiones administrativas" y el "uso de métodos cuantitativos para resolver problemas de decisiones gerenciales y de organización" (Gass y Fu, 2013, p. viii). En ese sentido, la ciencia de la administración es una expresión más de la teoría de la elección racional (*rational choice*) que Herbert A. Simon (1959)[^4] concibió como un comportamiento bajo una racionalidad limitada.  

En 1961 se institucionalizó la *investigación de operaciones y el análisis de sistemas* (*Operations Research and Systems Analysis, ORSA*) y, para 1967, la investigación de operaciones se atribuía a sí misma como objetivo la toma de decisiones (cf. Beer, 1967)[^5] y el *análisis de sistemas* se convirtió, *de facto*, en *análisis de decisiones*, sin usar ese término. Así, la ciencia de la administración se convirtió en una confluencia interdisciplinaria, que algunos autores como Witzel (2012)[^6] consideran que si bien surgió como disciplina del conocimiento en la década de 1950s, con la expansión del pensamiento administrativo a nivel mundial, es la consecuencia de la evolución del pensamiento de la Administración Científica (*Scientific Management*), propuesta por Frederick. W. Taylor a principios del siglo XX.  

Desde la década de 1970, la toma de decisiones agrupó las más diversas disciplinas, como las matemáticas, la sociología, la economía y la ciencia política (Buchanan y O’Connell, 2006, p. 32)[^7], así como las ciencias de la computación en la forma de la '*teoría de la información*', la '*cibernética*', la '*inteligencia artificial*' y el '*pensamiento sistémico*'. Así, las ciencias de la computación y la estadística fortalecieron el desarrollo de la investigación de operaciones dando origen al término '*análisis de decisiones*' (*decision analysis*), que alcanzó su auge en la década de 1980s.   

En la actualidad, el **análisis de decisiones** se considera: (1) un *campo multidisciplinario* o una *rama de la investigación de operaciones* que "usa las matemáticas aplicadas y el razonamiento científico para encontrar soluciones óptimas a problemas complejos" (Chen, Schauver y Chunk, 2009, p. 983)[^8], es decir, a problemas que involucran múltiples variables, objetivos, incertidumbres y restricciones, pero también múltiples involucrados (*stakeholders*) y tomadores de decisiones; (2) una **herramienta metodológica** que "permite la evaluación cuantitativa de la toma de decisiones bajo condiciones de incertidumbre" (idem); (3) una **filosofía** o **postura epistemológica** que pretende responder a preguntas tales como las siguientes "¿Cómo deben evaluarse las opciones cuando las consecuencias son inciertas? ¿Cuándo se tiene suficiente información para tomar una decisión? ¿Cuánto se debe pagar por nueva información que reduzca la incertidumbre? ¿Cuál es el nivel de riesgo 'correcto'?" (Call y Miller, 1990, pp. 116, 115)[^9].  

La UEA *Análisis de Decisiones* se enfoca en desarrollar las habilidades de *pensamiento estratégico cuantitativo* indispensables para la toma de decisiones complejas. Esta UEA es parte del paquete de UEAS cuantitativas de la Licenciatura en Administración y la primera de aplicación específica a la toma de decisiones. Estas habilidades van de la mano con el uso de computadoras digitales y software especializado, para que se percaten de la importancia que tiene en la administración de las empresas privadas, la administración pública y las organizaciones, en general.  

Considere el [programa oficial vigente de la UEA Análisis de Decisiones](http://csh.izt.uam.mx/sistemadivisional/SDIP/pac/2211092pe.pdf) y el [programa oficial vigente de Estadística I](http://csh.izt.uam.mx/sistemadivisional/SDIP/pac/2132044pe.pdf), la UEA prerrequisito.   

[Calendario UAM vigente](http://www.uam.mx/calendario/index.html).  


### Objetivos  

#### Objetivo General:  
Que al final del curso los alumnos sean capaces de:  
- Comprender a la toma de decisiones como un proceso sistematizado con un enfoque sistémico.  
- Identificar a la toma de decisiones como una forma equivalente de solucionar problemas en la administración.

#### Objetivos Específicos:
Que al finalizar el curso el alumno sea capaz de:
- Realizar la estructuración de problemas de decisión y seleccionar y aplicar el modelo de decisión en problemas de administración.
- Buscar y ponderar información relevante en fuentes diversas.
- Argumentar una propuesta crítica sobre un tema específico.


### Contenido Sintético

#### Unidad 0. Prerrequisitos
1. Prácticas:
   - *Práctica 0.1: Bases de trabajo colaborativo con Google Drive* (Demostrativa online).
   
      *Objetivo*: Aprender las operaciones con archivos y directorios en Google Drive, como un ejemplo de plataformas de cómputo en la nube.  
      
      Construya la estructura de directorios en [Google Drive](https://drive.google.com/drive/my-drive) para la entrega de controles de lectura, prácticas y proyecto final de acuerdo a un sistema de organización de archivos ([guía](https://www.youtube.com/watch?v=duNwB8xt2_w)). ([tutorial](https://www.youtube.com/watch?v=I3jii6ltINY&frags=pl%2Cwn)).

    - *Práctica 0.2: Instalación de software para grabación de audio y video* (Demostrativa online).
   
      *Objetivo*: Aprender a descargar e instalar un software para grabar video y una para audio y aprender a buscar tutoriales en YouTube para utilizarlo.
   
      *Parte 1*. Instale [vokoScreenNG](https://linuxecke.volkoh.de/vokoscreen/vokoscreen-download.html) o instale la aplicación de su preferencia.
          - Primero instale los prerrequisitos (vea [aquí](https://github.com/vkohaupt/vokoscreenNG): [codec pack](https://www.windows10codecpack.com/) y [GStreamer](https://gstreamer.freedesktop.org/pkg/windows/1.14.4/gstreamer-1.0-x86-1.14.4.msi); alternativamente, puede usar estos [codecs](https://codecguide.com/download_kl.htm)).
          - Alternativamente, puede usar [Open Broadcaster Software (OBS Studio)](https://obsproject.com/es)) (grabación, edición y transmisión de video) ([tutorial](https://www.youtube.com/watch?v=qLuSrSiC9Xc)), si los recursos de su computadora lo permiten.  
   
      *Parte 2*. Grabe su pantalla y capture la toma de la cámara y hable sobre las expectativas que tiene del curso usando el software (ver [tutorial](https://www.youtube.com/watch?v=mh5qV2iAiVs)). Puede agregar algún fondo musical. Busque en YouTube los tutoriales que le sirvan para completar la práctica con éxito. Al terminar suba sus videos y su audio a su Google Drive donde corresponda, según la estructura de directorios de la Práctica 0.1.

      *Parte 3*. Active su cuenta de [Office 365 Pro Plus](http://www.uam.mx/o365/) (software de oficina) e instale su copia de [Office Pro](http://www.uam.mx/ti/soft/microsoft.html) (software de oficina) (documente el proceso).
   
      *Parte 4*. Si tiene computadora en casa, descargue en instale el siguiente software: [*7-zip*](https://www.7-zip.org/download.html) (compresor/descompresor), [*LibreOffice*](https://www.libreoffice.org/) (suite de oficina), [*R*](https://www.r-project.org/) (estadística) y [*RStudio*](https://www.rstudio.com/) (estadística).
   
      *Parte 5*. Para la práctica en el salón, descargue e instale [*PortableApps*](https://portableapps.com/) ([tutorial 1](https://www.youtube.com/watch?v=Ux_3p4lDmTg), [tutorial 2](https://www.youtube.com/watch?v=Ux_3p4lDmTg)) en su USB vacía. Tome en cuenta que debe desactivar el antivirus para realizar la práctica y usar *PortableApps*. [guía](https://www.youtube.com/watch?v=HDEhLpS7UwM)). Luego, descargue e instale el siguiente software portable en una USB: *LibreOffice* (suite de oficina) ([portable](https://portableapps.com/apps/office/libreoffice_portable)), *7-zip* (compresor/descompresor) ([portable](https://portableapps.com/apps/utilities/7-zip_portable)), [*R Portable*](https://sourceforge.net/projects/rportable/files/R-Portable/)) (estadística) y [*RStudio Portable*](https://sourceforge.net/projects/rportable/files/R-Studio/) (estadística).

##### *Bibliografía Complementaria:*
- Ibiza, D. (2018, Apr 3). 1. Introducción a *Google Drive*: 
     1 Primeros pasos ([tutorial](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=330s))    
     2. Gestión de archivos y carpetas ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=2042s)), 3. Opciones de archivos y carpetas ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=3313s)), 4. Cómo compartir archivos y carpetas ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=4238s)), 5. Trabajar con documentos ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk&t=5222s)) . In Tutorial Google Drive | Completo | Principiantes | Paso a Paso. YouTube. (video). ([url](https://www.youtube.com/watch?v=aLPTDIS-8dk)).  


#### Unidad 1. Presentación
1. Introducción
2. Presentación del programa
3. Evaluación Global y de Recuperación
4. Prácticas:  
    - *Práctica 1.1: Preparación de RStudio Cloud*.  
  
      *Objetivo*: Aprender a preparar el entorno de *RStudio Cloud* para generar un libro *RMarkdown*.  
  
      Cree su cuenta en [RStudio cloud](https://posit.cloud/) que le permitirá ejecutar código fuente de R en la nube, hacer las modificaciones que requiera y usarlo para sus propias necesidades.  
  
    - *Práctica 1.2: Fundamentos de R y RStudio*. (Entrega: 27 de febrero de 2023).  
  
      *Objetivo*: Aprender a usar el R y RStudio en el entorno de *RStudio Cloud* y en su computadora personal.  
  
      Tome como base el pequeño libro [R para Análisis de Datos](https://bookdown.org/ddiannae/curso-rdata/) de Diana García Cortés (2022) y los recursos digitales disponibles por la autora en [Github](https://github.com/ddiannae/curso-rdata). Siga las instrucciones del libro y practique a discreción hasta dominar los temas.   
      
      Debe entregar son ejercicios de los siguientes capítulos del libro, cada uno en un script o archivo .R en su proyecto *RStudio cloud*.    

    - *Práctica 1.3: Creación de documentos con RMarkdown en RStudio Cloud*. (Entrega: 20 de febrero de 2023).

      *Objetivo*: Aprender los principios básicos de edición utilizando el lenguaje RMarkdown en *RStudio cloud* y, al mismo tiempo, aprender a manejar vectores, matrices y sus operaciones en R y su representación gráfica usando LaTeX.
    
      *Parte 1*. Descargue el archivo base [LinearAlgebraR-Handout.pdf](https://github.com/wangyi-fudan/BIOL130173/blob/master/LinearAlgebraR-Handout.pdf). Convierta el archivo *.pdf* a *.docx* y haga una traducción al español del documento base o busque el archivo traducido *LinearAlgebraR-Handout_ES.docx* en el canal de la clase en Telegram.  
      
      *Parte 2*. Tome como base el archivo traducido y cópielo a un archivo RMarkdown. Guárdelo con el mismo nombre en su proyecto de *RStudio cloud*. Edítelo con la sintaxis de RMarkdown y re-cree el archivo equivalente del archivo base *LinearAlgebraR-Handout.pdf*. 
      
      Tips:   
      * Para dibujar las fórmulas matemáticas, los vectores y las matrices, utilice un editor en línea como el editor de ecuaciones [HostMath](https://www.hostmath.com/) en LaTeX, cree las fórmulas e incruste el código correspondiente en su archivo RMarkdown (*.Rmd*).   
      * Descargue las imágenes y súbalas al directorio *images* en su proyecto y luego incrústelas adecuadamente con el códigocorrespondiente en su archivo *.Rmd* ([Campos, 2020](https://rpubs.com/Juve_Campos/ImagenesyMultimediaEnRmarkdown)).
      * Considere alguna de las siguientes guías en RMarkdown:
        - [Guía de R Markdown](https://gesel.github.io/materiales/10Gu%C3%ADa_RMarkdown.pdf) (Gualchi, 2019),
        - [Introducción al uso de RMarkdown para la compilación de resultados de RStudio en diferentes formatos](https://bookdown.org/gboccardo/manual-ED-UCH/introduccion-al-uso-de-rmarkdown-para-la-compilacion-de-resultados-de-rstudio-en-diferentes-formatos.html) (Boccardo Bosoni y Ruiz Bruzzone, 2019),
        - [40 Reports with R Markdown](https://epirhandbook.com/en/reports-with-r-markdown.html) (The Epidemiologist R Handbook, 2022),
        - [Aprende lo Básico de R Markdown en 20 Minutos](https://www.youtube.com/watch?v=6Qj8yBFgT9Q) (José Antonio: Estadística Aplicada, 2021, Aug 23) y 
        - [Ecuaciones (LaTeX) | Tutorial básico de R Markdown](https://www.youtube.com/watch?v=nd-YudmcLjQ) (DaniMedi, 2020, Sep 17).
      Concéntrese en desarrollar la capacidad de conseguir la ayuda para resolver satisfactoriamente la práctica y practique lo suficiente hasta que logre el objetivo.
      
      Al final, debe obtener el archivo .Rmd base para la generación de los archivos archivo HTML y PDF generados durante la conversión.
      
    - *Práctica 1.4: Bases de datos I: Bases de datos pequeñas*. (Entrega: 13 de marzo de 2023).   

      *Objetivo*: Aprender el manejo de archivos con R.
       
      *Parte 1*. Desde el sitio web del Inegi, del [Censo Nacional de Población y Vivienda del INEGI](https://www.inegi.org.mx/programas/ccpv/2010/), descargue el [Cuestionario Básico](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/cpv2010_cuest_basico_d.pdf), la [Descripción de la Base de Datos](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/diccionario_cuestionario_basico.xls).
    
      De la pestaña [Microdatos](https://www.inegi.org.mx/programas/ccpv/2010/#Microdatos), descargue la muestra de la base de datos de personas en formato DBF y comprimido (.ZIP) [dummy_personas_cpv2010_dbf.zip](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/microdatos/ejemplobd/dummy_personas_cpv2010_dbf.zip)), la muestra de la base de datos de viviendas en alguno de los otros formatos disponibles: SAV, DTA o SAS comprimido (.ZIP) y el Catálogo de la Integración General de Localidades (CIGEL) (archivo [cigel_2010_hab_dbf.zip](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/cigel_2010_hab_dbf.zip) en formato DBF comprimido).
    
      También descargue el archivo [DUMMY_PERSONAS_5K.dbf.zip](https://drive.google.com/file/d/1TNXXZZQ9GEJKU8UD-YyuklF4a1E8w_0b/view?usp=sharing), que es una muestra muy pequeña de la base de datos, para realizar el ejercicio.
    
      *Parte 2*. Utilice el paquete [*rio*](https://cran.r-project.org/web/packages/rio/) en *RStudio* para abrir (importar) los archivos del Inegi de la Parte 1 (DBF, SAS, SAV, DTA). Después de importar el archivo, expórtelo a XLSX, en su directorio de trabajo. Por último, convierta otro archivo de XLSX a CSV. Tome como base el script en R [manejo de archivos del inegi.R](https://drive.google.com/file/d/15W7CjN2TmjFo5OSXbbftaWCwm8DagNWo/view?usp=sharing) y cámbielo y adáptelo a su contexto particular, hasta que funcione correctamente.       
  
      *Parte 4*. Reflexione y responda: *¿Qué diferencias existen entre las tres operaciones básicas que proporciona el paquetew rio de R?* Consulte la ayuda del paquete *rio* para que conozca el alcance del mismo.  
      
      *Parte 5*. Por último, estudie las instrucciones de *manipulación de archivos* con R con el tutorial [R Manipulation of Files and Directories](https://felixfan.github.io/File-Manipulation/) al convertirlo en un archivo RMarkdown.  
      
      Saque sus conclusiones y documente su experiencia en la realización de la actividad en un video de hasta 10 minutos, a modo de tutorial. Suba los archivos creados o modificados a su proyecto de RStudio, donde corresponda.   

##### *Bibliografía Obligatoria:*   
- Universitat de les Illes Balears. Som UIB (2021). MOOC Aprende R : Introducción al tratamiento de datos con R y RStudio. *YouTube*. ([url](https://www.youtube.com/playlist?list=PLnXFIHWLWQXFOIOdpAv2ioBHQuYgV7x2t)).  

#### Unidad 2. De la 'Teoría de la Elección Racional' al 'Análisis de Decisiones'
1. La ciencia de la administración y la toma de decisiones
2. Toma de decisiones, teoría de la elección racional, racionalidad limitada y cibernética
3. ¿Qué es el análisis de decisiones?
4. Alcances y limitaciones del análisis de decisiones
5. Tareas y Prácticas:
    - *Tarea 2.1: ¿Qué es el Análisis de Decisiones?*. (Entrega: 13 de marzo de 2023).   
  
      *Objetivo*: Aprender qué es el análisis de decisiones, su contexto y aplicación.  
  
      Lea el capítulo 1 del libro *Decision Analysis for Managers: A Guide for Making Better Personal and Business Decisions* de David Charlesworth (2017), en su versión epub o en su traducción al español. Estudie las preguntas y respuestas del autor y elabore sus propias reflexiones. Escríbalas en sus cuaderno. Luego, elabore un archivo Rmarkdown en su proyecto de RStudio en [posit.cloud](https://posit.cloud) y súbalo a su proyecto con el nombre de la tarea.
      
      Coordínese con los demás compañeros y elabore una versión en español de las figuras del capítulo del libro, si es que así lo requiere. De ser necesario, complemente con la lectura de Howard (1988).          
      
    - *Tarea 2.2: ¿Cómo enmarcar un problema de Análisis de Decisiones*. (Entrega: 13 de marzo de 2023).   
  
      *Objetivo*: Aprender a enmarcar un problema de análisis de decisiones.  
  
      Lea el capítulo 2 del libro *Decision Analysis for Managers: A Guide for Making Better Personal and Business Decisions* de David Charlesworth (2017), en su versión epub o en su traducción al español.    
      
      Responda a las dos preguntas centrales: (1) ¿Qué es un problema de decisión? y (2) ¿Cómo debe plantearse y documentarse un problema de decisión? Parta de los argumentos del autor y desarrolle sus propias reflexiones en un archivo Rmarkdown, en su proyecto de RStudio en [posit.cloud](https://posit.cloud). Coordínese con los demás compañeros y elabore una versión en español de las figuras del capítulo del libro.    

### Bibliografía:
- Howard, R. A. (1988). Decision analysis: practice and promise, *Management Science, 34*(6), 679-695. ([url](https://www.jstor.org/stable/2632123)) ([pdf](https://sci-hub.ru/10.2307/2632123))
- Charlesworth, D. (2017). Decision analysis for managers: A guide for making better personal and business decisions. New York: Business Expert Press. [Amazon](https://www.amazon.com/-/es/David-Charlesworth-ebook/dp/B06ZY9XRTW) ([epub](https://libgen.rs/book/index.php?md5=10EE672DF770CEFD216D6F65C29FE2C1)) (traducción: [Análisis de decisiones para gerentes](https://libgen.rs/book/index.php?md5=D43F87667B1D27665BE199267253DBA9)


#### Unidad 3. Los problemas de decisión
1. Modelación de los problemas de decisión
2. Proceso de resolución de problemas de decisión
3. Estructuración de problemas de decisión
4. Modelos de decisión: 
   - Matriz de pagos
   - Árboles de decisión
   - Modelo de scoring
   - Modelo de norma mínima
   - Otras técnicas

### Bibliografía:
- Howard, R. A., & Abbas, A. E. (2016). Foundations of decision analysis [Global Edition]. Great Britain: Pearson Education. ([url](http://libgen.rs/book/index.php?md5=4B19F574BA8246A5BA274A7AF4BFB6A5)).
- Drury, C. (2020). [*Management and cost accounting*](http://libgen.rs/book/index.php?md5=32C869373F6352B932D6EF56FB9CD9D4). USA: Cengage Learning EMEA.   
- Howard, R. A. (1968). The foundations of decision analysis. *IEEE Transactions on Systems Science and Cybernetics, 4*(3), 211-219. ([url](https://ieeexplore.ieee.org/abstract/document/4082150)) ([pdf](https://sci-hub.ru/10.1109/TSSC.1968.300115)).
- Ley-Borrás, R. (2015). Deciding on the decision situation to analyze: The critical first step of a decision analysis. *Decision Analysis, 12*(1), pp. 46-58. ([pdf](https://sci-hub.se/10.1287/deca.2014.0308)).  
- Keeney, R. L. (2007). Developing objectives and attributes. *In* W. Edwards, R. F. Miles y D. von Winterfeldt. (2007). [*Advances in Decision Analysis: From foundations to applications*](http://libgen.rs/book/index.php?md5=AE826E7206D6FE17FD495BDB3BE0BC7B) (pp. 104-128), Cambridge: Cambridge University Press.
- Ralph L. Keeney, R. L. (1982). Feature article - Decision Analysis: An overview. *Operations Research, 30*(5), 803-838. ([pdf](https://pubsonline.informs.org/doi/pdf/10.1287/opre.30.5.803)).  
- Rios, S. (1994). [Decision theory and decision analysis: Trends and challenges](https://libgen.rs/book/index.php?md5=174BD23546E097199CECBDBA593D2521). New York: Springer Science+Business Media.
- Ríos, S., Ríos, D., Mateos, A. y Martín, J. (1998). *Programación lineal y aplicaciones: Ejercicios resueltos*. México: Alfa Omega Ra Ma. ([pdf](http://libgen.rs/main/C3553551396E715FAD11F850D70DF9F2)).
- Rojas, G., Fernandez, E., Whitney, C., Luedeling, E. & Cuneo, I. F. (2021). Adapting sweet cherry orchards to extreme weather events: Decision analysis in support of farmers "Investments in Central Chile." *Agricultural Systems* 187(February): 103031. DOI: https://doi.org/10.1016/j.agsy.2020.103031 . ([url](https://sci-hub.ru/10.1016/j.agsy.2020.103031)). ([video](https://www.youtube.com/watch?v=kpsqzkeg53Y)). (**Estudio de caso**).
- Smith, J. E. y von Winterfeldt, D. (2004). Decision Analysis in "Management Science". *Management Science, 50*(5), 561-574. ([pdf](https://sci-hub.ru/10.2307/30046097)).  
- Fox, J. (2016). Applied regression analysis and generalized linear models*. Thousand Oaks, CA: Sage. ([pdf](https://libgen.rs/book/index.php?md5=51DA2C83D6A72D575E6BD179DD61DFE6)). 	

- Anónimo. (2023). [Decision trees in R Analytics](https://techvidvan.com/tutorials/decision-tree-in-r/) [Tutorial En Línea] TechVidvan.
- Anónimo. (2023). [Decision trees in R Analytics](https://techvidvan.com/tutorials/decision-tree-in-r/) [Tutorial En Línea]. TechVidvan. (datos en el paquete ISLR).
- Anónimo. (2017). [R decision trees: The best tutorial on tree based modeling in R!](https://data-flair.training/blogs/r-decision-trees/) [Tutorial En Línea]. DataFlair. ([datos](https://goo.gl/At238b)).
- Chicaiza, A. (2020). [Modelo de otorgamiento de crédito (AD Science Analytics)](https://rpubs.com/Alex_Deiiv/CreditScoring). RPubs. (Datos en xls: [German Credit Case Data](https://ocw.mit.edu/courses/15-062-data-mining-spring-2003/3d0fbded046c53a5fb72d3bcd2064ac9_GermanCredit.xls)) ([Otra versión](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)) de German Credit Case Data).
- Nijs, V. R. (2019). [Radiant: Business analytics using R and Shiny](https://radiant-rstats.github.io/docs/index.html). ([Paquete en CRAN](https://cran.r-project.org/web/packages/radiant.data/readme/README.html)) ([Código fuente](https://github.com/radiant-rstats)) ([Documentación](https://radiant-rstats.github.io/docs/)) ([Instalación](https://radiant-rstats.github.io/docs/install.html)) ([Canal en YouTube](https://www.youtube.com/@RadiantForR/featured))
- Deehr, J. (2017, Aug 28). [Multi objective decision analysis [MODA] in R](https://rstudio-pubs-static.s3.amazonaws.com/300421_0e5019919ff146ab9d16e27b09fbf767.html). RPubs. [DecisionAnalysis-package: DecisionAnalysis: Multi-Objective Decision Analysis [MODA]](https://rdrr.io/github/AFIT-R/MODA/man/DecisionAnalysis-package.html#heading-0). ([Datos](http://nflsavant.com/)) ([traducción](https://rstudio--pubs--static-s3-amazonaws-com.translate.goog/300421_0e5019919ff146ab9d16e27b09fbf767.html?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=en&_x_tr_pto=wapp)).
- AFIT Data Science Lab. (2018). DecisionAnalysis. [[AFIT-R/MODA: Implementation of Multi Objective Decision Analysis](https://rdrr.io/github/AFIT-R/MODA/)]. RDRR. [[Código fuente en GitHub](https://github.com/AFIT-R/DecisionAnalysis)].  
- Kuhn, M. & Silge, J. (2022,Dec 20). [Tidy modeling with R: A framework for modeling in the tydiverse](https://www.tmwr.org/). O'Reilly. ([GitHub](https://github.com/tidymodels/TMwR)).  

### Bibliografía General:

- Recursos digitales en la UAM: biblioteca de la Unidad Iztapalapa ([url](http://contingencia.izt.uam.mx/wp-content/uploads/2020/04/Biblioteca-Nuevo-3b-bindani-B.pdf)), biblioteca digital ([url](https://bidi.uam.mx/index.html)), [recursos varios](http://pcyti.izt.uam.mx/recursos/infext/infoext.html).  
- Recursos controversiales: [Library Genesis](http://gen.lib.rus.ec/) (libros, artículos, novelas), [**SciHub**](https://sci-hub.se/about) (artículos), [The Pirate Bay](https://thepiratebay.org/index.html) (P2P file sharing network) (archivos), [Academic Torrents](http://academictorrents.com/) (artículos, datos y cursos).
- Repositorios de software: [Software para la comunidad UAM](https://www.uam.mx/ti/soft/), [AlternativeTo](https://alternativeto.net/), [SourceForge](https://sourceforge.net/), [CDLibre](https://www.cdlibre.org/), [Software Heritage](https://www.softwareheritage.org/?lang=es), [GitHub](https://github.com/github).
 
- Valcheva, S. (s.f.). 10 Open Source Decision Tree Software Tools. ([url](https://www.intellspot.com/open-source-decision-tree/)).

- Walum, H., & De Leon, D. (2022). Teacups, giraffes, & statistics (Tazas de té, jirafas y estadística). GitHub. [Módulos](https://tinystats.github.io/teacups-giraffes-and-statistics/) [Proyecto en RMarkdown](https://github.com/tinystats/teacups-giraffes-and-statistics) [Una deliciosa serie de módulos para aprender estadística y codificación en R para estudiantes, científicos y entusiastas de la estadística.]
- Guisande González, C. & Vaamonde Liste, A. (2013). [Gráficos estadísticos y mapas con R](https://libgen.rs/book/index.php?md5=8ECF29580BFE702F21D16CC2C9BDBA5C). España: Díaz de Santos.
- Universitat de les Illes Balears. Som UIB (2016, Sep 22). MOOC Aprende R : Introducción al tratamiento de datos con R y RStudio. *YouTube*. ([Lista de videos](https://www.youtube.com/playlist?list=PLnXFIHWLWQXFOIOdpAv2ioBHQuYgV7x2t)).
- Teetor, P. (2019).  [*R cookbook: Proven recipes for data analysis, statistics, and graphics*]. O'Reilly. [Online] ([traducción al español](https://translate.google.com/translate?sl=en&tl=es&u=https://rc2e.com/)).
- RStudio cheatsheets. ([url](https://github.com/rstudio/cheatsheets)).  
- Wickham, H. & Grolemund, G. (2017). [*R for data science: Import, tidy, transform, visualize, and model data*](https://r4ds.had.co.nz/). O'Reilly. ([R para ciencia de datos](https://es.r4ds.hadley.nz)). ([Solución de los ejercicios](https://cienciadedatos.github.io/r4ds-soluciones/index.html)).  

## Modalidades de Evaluación

### Evaluación Global
La asistencia puntual a la clase es obligatoria según el reglamento de estudios. Para tener derecho a presentar los exámenes debe tener una asistencia superior o igual al 80%. Es importante la *participación activa clase a clase*. La falta de participación en clase y la no entrega de sus reportes de prácticas a lo largo del trimestre tendrá repercusiones en la evaluación final que puede llegar a la reprobación del curso. Ver porcentajes de ponderación de calificación.

#### Calificación
| Factor | Porcentaje | Observaciones |
| --- | :---: | ------------- |
| Tareas|30% |Se entrega en la fecha programada |
| Prácticas| 30% |Se entregan  en la fecha programada |
| Exámenes| 40% | Primero (a), Segundo (b)|
| Total | 100% | |

**Notas:
  - **a).** Primer examen: *Teórico* y *Práctico*: Fecha: por definir. 
  - **b).** Segundo examen: *Teórico - Práctico*: Fecha: por definir. 
  - **Evaluación Global:** Quienes no hayan aprobado los exámenes tendrán oportunidad de aplicar una evaluación global teórico-práctica de todo el curso (Teoría y Práctica). La misma oportunidad es para quienes tengan baja calificación o deseen subir. 
  - **Entrega de calificaciones:** Fecha por definir.

### Evaluación de Recuperación
La *evaluación de recuperación* no será aplidada por el profesor, sino por la Coordinación de la Licenciatura en Administración, de acuerdo a las políticas definidas por la misma y será realizada según el calendario vigente. Por lo que deberá coordinarse con el Coordinador de la Licenciatura.

**Notas:**
[^1]: Jaiswal, N. K. (1997). *Military operations research: Quantitative decision making*. New York: Springer Science+Business Media.
[^2]: Gass, S. I. y Fu, M. C. (2013). Preface. *In* Saul I. Gass y Michael C. Fu (Eds.). *Encyclopedia of operations research and management science*. New York, Heidelberg, Dordrecht, London: Springer
[^3]: Hitch, C. (1955). An appreciation of systems analysis. *Journal of the Operations Research Society of America, 3*(4), 466-481.
[^4]: Simon, H. A. (1955). A behavioral model of rational choice. *The Quarterly Journal of Economics, 69*(1) (Feb), 99-118.
[^5]: Beer, S. (1967). *Management science: The business use of operations research*. Doubleday
[^6]: Witzel, M. (2012). *A History of Management Thought*. London: Routledge.
[^7]: Buchanan, L y O'Connell, A. (2006). A brief history of decision making. *Harvard Business Review, 84*(1), 32-41, 132.
[^8]: Chen, N. C., Shauver, M. J., & Chung, K. C. (2009). A primer on use of decision analysis methodology in hand surgery. *The Journal of Hand Surgery, 34*(6), 983-990.
[^9]: Call, H. J., y Miller, W. A. (1990). A comparison of approaches and implementations for automating decision analysis. *Reliability Engineering & System Safety, 30*(1-3), 115-162.
