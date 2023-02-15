<img src="https://github.com/jzavalar/2211088-informatica/blob/main/conjunto-baseIzt.png" alt="UAM Iztapalapa" width="60%"/>

## Programa Analítico de la UEA An (Teoría y Práctica)
## Licenciatura en Administración

**Clave de la UEA:** *2211092*, **Grupos:** *HE51* y *HE12*, **Trimestre:** *22-I*

**Horario:** *Lunes y miércoles* de *14:00 a 16:00*.

**Salón:** Anexo A, Sala J (AA-J).

**Asesorías:**  *Martes* de *20:00* a *22:00 hr*, vía [Telegram](https://telegram.org/apps), previa solicitud.

**Profesor:** *dr. Jesús Zavala Ruiz*

**Contacte al profesor**:
- Correo electrónico: [jzr@xanum.uam.mx](mailto:jzr@xanum.uam.mx)
- Telegram: <img src="https://github.com/jzavalar/2211088-informatica/blob/main/telegram_logo.svg" alt="Telegram" width="3%"/> [@jzavalar](https://telegram.me/jzavalar)


### Introducción

Afines de los años 1930s, a solicitud del gobierno británico, el profesor P.M.S. Blackett y su equipo de científicos e ingenieros desarrollaron métodos para “resolver problemas técnicos relacionados con el desarrollo de nuevas armas y equipo durante la Segunda Guerra Mundial” (Jaiswal, 1997, p. 2)[^1], con un enfoque hacia problemas técnicos operativos (p. 4). Según, este autor, después de la Segunda Guerra Mundial, los científicos e ingenieros asociados con el profesor Blackett pasaron de la industria militar a los sectores civiles como el transporte, la salud y la industria, convencidos de que podían analizar esas operaciones con las mismas herramientas analíticas (p. 4).

Así surgió la **investigación de operaciones** (*operations research*) que se concibió como una "colección de herramientas y técnicas que podían utilizarse para mejorar sistemas bajo el control de un encargado independientemente de su campo de la actividad" (idem). El arsenal metodológico y computacional de la posguerra incluyó la programación lineal, la teoría de juegos, la programación dinámica, la simulación de eventos discretos con la computadora digital, adicionalmente a las teorías de inventarios y colas, el modelado de Markov y los métodos básicos de optimización. Actualmente, la *investigación de operaciones* se define como "la aplicación de los métodos de la ciencia a problemas complejos que se presentan en la dirección y la administración de grandes sistemas de hombres, máquinas, materiales y dinero, en la industria, los negocios, el gobierno y la defensa" (Gass y Fu, 2013, p. viii) [^2]; aunque también se define como “la ciencia de decidir cómo obtener el mejor diseño y cómo operar los sistemas hombre-máquina” y como “un método científico para proveer de los departamentos ejecutivos una base cuantitativa para la toma de decisiones” (idem).

La investigación de operaciones derivó en el ‘*análisis de sistemas*’ asociado a la *toma de decisiones*, considerada para entonces como “el examen sistemático de las distintas alternativas” (Hitch, 1955, p. 477)[^3] que se atribuyó como competencia de los gerentes (*managers*). En cambio, el llamado '*análisis puro'* estaba relacionado con la logística oper^ativa y era realizado por los 'técnicos' (*technicians*) o analistas (*analysts*). Así, el *análisis de sistemas* se puede considerar como “un enfoque sistemático para ayudar a un tomador de decisiones (*decision maker*) que elija un curso de acción, investigando su problema completo, buscando objetivos y alternativas y comparándolas considerando sus consecuencias, usando un marco de referencia apropiado -tan analítico como sea posible- para invocar el juicio y la intuición de expertos sobre el problema" (Jaiswal, 1997, p. 5). Esta definición sugiere que debe considerarse que *un ciclo de toma de decisiones* consiste desde "la definición de los objetivos, la exploración de las alternativas y su evaluación en términos de sus costos(/beneficios) y eficacia” (idem).

Desde los años 1950s, el concepto de *análisis de sistemas* ha permanecido, hasta nuestros días, asociado a la ‘toma de decisiones’, a la ‘administración de proyectos’ y otras disciplinas, siempre persiguiendo el mismo objetivo: *decidir racionalmente ante la incertidumbre*. Como consecuencia, surgieron las *ciencias de la administración* como un enfoque interdisciplinario que pasó de la eficiencia técnica a la eficacia de los sistemas sociotécnicos. Formalmente, la *ciencia de la administración* (*management science*) se define como la "aplicación de la metodología o los principios científicos a las decisiones administrativas" y el "uso de métodos cuantitativos para resolver problemas de decisiones gerenciales y de organización" (Gass y Fu, 2013, p. viii). En ese sentido, la ciencia de la administración es una expresión más de la teoría de la elección racional (*rational choice*) que Herbert A. Simon (1959)[^4] concibió como un comportamiento bajo una racionalidad limitada.
^
En 1961 se institucionalizó la *investigación de operaciones y el análisis de sistemas* (*Operations Research and Systems Analysis, ORSA*) y, para 1967, la investigación de operaciones se atribuía a sí misma como objetivo la toma de decisiones (cf. Beer, 1967)[^5] y el *análisis de sistemas* se convirtió, *de facto*, en *análisis de decisiones*, sin usar ese término. Así, la ciencia de la administración se convirtió en una confluencia interdisciplinaria, que algunos autores como Witzel (2012)[^6] consideran que si bien surgió como disciplina del conocimiento en la década de 1950s, con la expansión del pensamiento administrativo a nivel mundial, es la consecuencia de la evolución del pensamiento de la Administración Científica (*Scientific Management*), propuesta por Frederick. W. Taylor a principios del siglo XX.

Desde la década de 1970, la toma de decisiones agrupó las más diversas disciplinas, como las matemáticas, la sociología, la economía y la ciencia política (Buchanan y O’Connell, 2006, p. 32)[^7], así como las ciencias de la computación en la forma de la *teoría de la información*, la *cibernética*, la *inteligencia artificial* y el *pensamiento sistémico*. Así, las ciencias de la computación y la estadística fortalecieron el desarrollo de la investigación de operaciones dando origen al término *análisis de decisiones* (*decision analysis*), que alcanzó su auge en la década de 1980s.  

En la actualidad, el **análisis de decisiones se considera**: (1) un **campo multidisciplinario** o una *rama de la investigación de operaciones* que “usa las matemáticas aplicadas y el razonamiento científico para encontrar soluciones óptimas a problemas complejos” (Chen, Schauver y Chunk, 2009, p. 983)[^8], es decir, a problemas que involucran múltiples variables, objetivos, incertidumbres y restricciones, pero también múltiples involucrados (*stakeholders*) y tomadores de decisiones; (2) una **herramienta metodológica** que “permite la evaluación cuantitativa de la toma de decisiones bajo condiciones de incertidumbre” (idem); (3) una **filosofía** o **postura epistemológica** que pretende responder a preguntas tales como las siguientes “¿Cómo deben evaluarse las opciones cuando las consecuencias son inciertas? ¿Cuándo se tiene suficiente información para tomar una decisión? ¿Cuánto se debe pagar por nueva información que reduzca la incertidumbre? ¿Cuál es el nivel de riesgo ‘correcto’?” (Call y Miller, 1990, pp. 116, 115)[^9].

La UEA *Análisis de Decisiones* se enfoca en desarrollar las habilidades de *pensamiento estratégico cuantitativo* indispensables para la toma de decisiones complejas. Esta UEA es parte del paquete de UEA cuantitativas de la Licenciatura en Administración y la primera de aplicación específica a la toma de decisiones. Estas habilidades van de la mano con el uso de computadoras digitales y software especializado, para que se percaten de la importancia que tiene en la administración de las empresas privadas, la administración pública y las organizaciones, en general.

Considere el [programa oficial vigente de la UEA](http://csh.izt.uam.mx/sistemadivisional/SDIP/pac/2211092pe.pdf) y el [programa oficial vigente de Estadística I](http://csh.izt.uam.mx/sistemadivisional/SDIP/pac/2132044pe.pdf), la UEA prerrequisito.

[Calendario UAM vigente](http://www.uam.mx/calendario/index.html).


### Objetivos 

#### Objetivo General:
Que al final del curso los alumnos sean capaces de:
- Comprender a la toma de decisiones como un proceso sistematizado con un enfoque sistémico.
- Identificar a la toma de decisiones como una forma equivalente de solucionar problemas en la administración.

#### Objetivos Específicos:
Que al finalizar el curso el alumno sea capaz de:
- Realizar la estructuración de problemas de decisión en la administración, seleccionar y aplicar en problemas de administración el modelo de decisión.
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
  
      Cree su cuenta en [RStudio cloud](https://rstudio.cloud/). Esto le permitirá ejecutar el código fuente de las recetas del libro, hacer las modificaciones que requiera y usarlas para sus propias necesidades.  
  
      Por último, haga un video tutorial grabando la pantalla de su equipo con [Vokoscreen-NG](https://linuxecke.volkoh.de/vokoscreen/vokoscreen.html) conforme vaya realizando su práctica hasta que haya cumplido el objetivo. Suba su video a su cuenta de Google Drive donde corresponda. 
  
    - *Práctica 1.2: Fundamentos de R y RStudio*.  (Entrega: 20 de febrero de 2023).  
  
      *Objetivo*: Aprender a usar el R y RStudio en el entorno de *RStudio Cloud* y en su computadora personal.  
  
      Tome como base el pequeño libro [R para Análisis de Datos](https://bookdown.org/ddiannae/curso-rdata/) de Diana García Cortés (2022) y los recursos digitales disponibles por la autora en [Github](https://github.com/ddiannae/curso-rdata). Siga las instrucciones del libro y practique a discreción hasta dominar los temas.   
      
      Por último, haga un video tutorial grabando la pantalla de su equipo conforme vaya realizando su práctica hasta que haya cumplido el objetivo. Suba su video a su cuenta de Google Drive donde corresponda y al chat de Telegram con el profesor.   

    - *Práctica 1.3. Bases de datos I: Bases de datos pequeñas*. (Entrega: 20 de febrero de 2023).  

      *Objetivo*: Aprender los principios de una base de datos y usar tablas dinámicas y filtros para la resolución de preguntas cuantitativas.
    
      *Parte 1*. Desde el sitio web del Inegi, del [Censo Nacional de Población y Vivienda del INEGI](https://www.inegi.org.mx/programas/ccpv/2010/), descargue el [Cuestionario Básico](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/cpv2010_cuest_basico_d.pdf), la [Descripción de la Base de Datos](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/diccionario_cuestionario_basico.xls), una [muestra de la base de datos](https://www.inegi.org.mx/programas/ccpv/2010/), la [Síntesis Metodológica y Conceptual](http://internet.contenidos.inegi.org.mx/contenidos/Productos/prod_serv/contenidos/espanol/bvinegi/productos/metodologias/est/sm_cpv2010.pdf) y el [Cuestionario Ampliado](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/cpv2010_cuest_ampliado_d.pdf).
    
      De la pestaña [Microdatos](https://www.inegi.org.mx/programas/ccpv/2010/#Microdatos), descargue la muestra de la Base de Datos de Personas ([dbf en zip](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/microdatos/ejemplobd/dummy_personas_cpv2010_dbf.zip)), Base de Datos de Viviendas ([dbf en zip](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/microdatos/ejemplobd/dummy_viviendas_cpv2010_dbf.zip)) y el Catálogo de la Integración General de Localidades (CIGEL) ([dbf en zip](https://www.inegi.org.mx/contenidos/programas/ccpv/2010/doc/cigel_2010_hab_dbf.zip)) y los demás catálogos.
    
      También descargue el archivo [DUMMY_PERSONAS_5K.dbf.zip](https://drive.google.com/file/d/1TNXXZZQ9GEJKU8UD-YyuklF4a1E8w_0b/view?usp=sharing), que es una muestra muy pequeña de la base de datos, para realizar el ejercicio.
    
      *Parte 2*. En primer lugar, utilice *Calc* de *LibreOffice* ([ayuda](https://help.libreoffice.org/Calc/Importing_and_Exporting_dBASE_Files/es)) para abrir el archivo disponible del Inegi en el formato DBF y expórtelo a cualquier otro como XLSX, XLS o CSV. En segundo lugar, utilice el paquete [*rio*](https://cran.r-project.org/web/packages/rio/) en [*RStudio*](https://rstudio.com/) para abrir (importar / exportar) y convertir alguno de los archivos en los formatos disponibles del Inegi: DBF, SAS, SAV, DTA a cualquier otro como XLSX, XLS o CSV. Básese en [este script](https://drive.google.com/file/d/15W7CjN2TmjFo5OSXbbftaWCwm8DagNWo/view?usp=sharing) y adáptelo a su caso particular hasta que le funcione correctamente.
    
      *Parte 3*. Practique la consulta multidimensional de datos con la pequeña muestra de la base de datos descargada en la Parte 1 (DUMMY_PERSONAS_5K.dbf). Luego, revise la metodología y la solución en *Google Sheets* (en *Google Drive*) [aquí](https://drive.google.com/file/d/1Uqu6m_Fv1AqR5Nf8H_8JbffWmr_L01si/view?usp=sharing) y haga lo equivalente en *Excel* (*Microsoft Office*) y en *Calc* (*LibreOffice*).  
  
      Tome como base la siguiente pregunta compuesta:      
          - *¿Cuántos jefes de familia hay en la base de datos que son estudiantes y son menores de edad?* y  
          - *¿Cuál es su distribución por edad y sexo?*  
  
      *Tip*: Si bien, este problema puede resolverse aplicado filtros de manera consecutiva, también puede resolverse realizando una consulta a la base de datos mediante una tabla dinámica.  
  
      *Parte 4*. Repita la práctica y resuélvala con RStudio, usando un archivo Rmarkdown. Entregue el archivo fuente y el HTML generado.  
      
      Saque sus conclusiones y documente su experiencia en la realización de la actividad en un video de hasta 10 minutos, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.   

##### *Bibliografía Obligatoria:*
- Universitat de les Illes Balears. Som UIB (2021). MOOC Aprende R : Introducción al tratamiento de datos con R y RStudio. *YouTube*. ([url](https://www.youtube.com/playlist?list=PLnXFIHWLWQXFOIOdpAv2ioBHQuYgV7x2t)).  


#### Unidad 2. De la Teoría de la Elección Racional al Análisis de Decisiones
1. La ciencia de la administración y la toma de decisiones
2. Toma de decisiones, teoría de la elección racional, racionalidad limitada y cibernética
3. ¿Qué es el análisis de decisiones?
4. Alcances y limitaciones del análisis de decisiones
5. Tareas y Prácticas:
    - *Tarea 2.1: ¿Qué es el Análisis de Decisiones?*. (Entrega: 27 de febrero de 2023).   
  
      *Objetivo*: Aprender qué es el análisis de decisiones, su contexto y aplicación.  
  
      Lea el capítulo 1 del libro *Análisis de decisiones para gerentes: Una guía para tomar mejores decisiones personales y comerciales* de [David Charlesworth (2017)](https://www.amazon.com/-/es/David-Charlesworth-ebook/dp/B06ZY9XRTW) con las preguntas y respuestas argumentadas del autor y sus propias reflexiones en un archivo Rmarkdown en su proyecto de RStudio en [posit.cloud](https://posit.cloud). Coordínese con los demás compañeros y elabore una versión en español de las figuras del capítulo del libro.    
      
    - *Tarea 1.5: ¿Cómo enmarcar un problema de Análisis de Decisiones*. (Entrega: 29 de febrero de 2023).   
  
      *Objetivo*: Aprender a enmarcar un problema de análisis de decisiones.  
  
      Lea el capítulo 2 del libro *Análisis de decisiones para gerentes: Una guía para tomar mejores decisiones personales y comerciales* de [David Charlesworth (2017)](https://www.amazon.com/-/es/David-Charlesworth-ebook/dp/B06ZY9XRTW). Responda a las dos preguntas centrales: ¿Qué es un problema de decisión? y ¿Cómo debe plantearse y documentarse? Parta de los argumentos del autor y desarrolle sus propias reflexiones en un archivo Rmarkdown, en su proyecto de RStudio en [posit.cloud](https://posit.cloud). Coordínese con los demás compañeros y elabore una versión en español de las figuras del capítulo del libro.    

- *Tarea 2.1*: *Teoría de las bases de datos relacionales*. (Fecha de entrega: 25 de marzo de 2022).  

      Resuelva el siguiente cuestionario ([parte 1](https://drive.google.com/file/d/17IhZFgxB1XCeEYaJjTIJxKQQ-Rv1Vs2q/view?usp=sharing), [parte 2](https://drive.google.com/file/d/1zswLrAe5IBZXhq3YylAR5Sk_EhKdGiAH/view?usp=sharing), [parte 3](https://drive.google.com/file/d/1rdmW5IvGtipYRR4W8Yxhh8sbNOlB2ct2/view?usp=sharing)) en su cuaderno de apuntes para que refuerce la teoría, a partir de la siguiente [presentación](https://drive.google.com/file/d/1leDmRFqWQygcwnYro9315PeUGWjXIF0V/view?usp=sharing) sobre el tema.  
  
      Suba las fotos (legibles) de la tarea a su cuenta de *Google Drive*, en la carpeta respectiva, con el nombre de la tarea.  
  
      Saque sus conclusiones y documente en un video la realización de la tarea y su experiencia en la realización de la actividad, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.  
  
      **Bibliografía**: Quiroz, J. (2003). El modelo relacional de bases de datos. *Boletín de Política Informática (INEGI)*, (6), 53-61. ([pdf](http://ingenieriasimple.com/conred/el%20modelo%20relacional.pdf)). 

    - *Tarea 2.3*: *Cuestionario*. (Fecha de entrega: 30 de marzo de 2022).  

      *Objetivo*: Aprender el lenguaje de uso en la unidad.
  
      Resuelva el siguiente [cuestionario](https://github.com/jzavalar/2211092-Analisis_de_Decisiones/blob/main/Unidad%202.%20Cuestionario.md) en su cuaderno de apuntes, para que refuerce la teoría sobre el tema de la Unidad.  
  
      Suba las fotos (legibles) de la tarea a su cuenta de *Google Drive*, en la carpeta respectiva, con el nombre de la tarea.  
  
      Saque sus conclusiones y documente en un video la realización de la tarea y su experiencia en la realización de la actividad, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.  

 
5. Tareas y prácticas:
    - *Práctica 3.1*: *Operaciones matriciales con R y aplicaciones*. (Fecha de entrega: 10 de abril de 2022).
  
      *Objetivo*: Realizar un recordatorio sobre los vectores, las matrices y sus operaciones, usando R, como preparación para su aplicación en la programación lineal.  

      *Parte 0. Preparación*. Previamente debe abrir su cuenta en [RStudio.cloud](https://rstudio.cloud/). En su proyecto de la UEA, cree un folder con el nombre la práctica, para que ahí genere sus archivos correspondientes.  
  
      *Parte 1. Vectores en R*. Convierta el siguiente tutorial sobre [Vectores en R](https://r-coder.com/vectores-r/) en un archivo RMarkdown (.Rmd) y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final, escriba sus propias conclusiones.  
  
      *Parte 2. Matrices en R*. Convierta el siguiente tutorial sobre [Matrices en R](https://r-coder.com/matrices-r/) en un archivo RMarkdown (.Rmd) y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final escriba sus propias conclusiones.  
  
      *Parte 3. Operaciones con Matrices en R*. Convierta el siguiente tutorial sobre [Operaciones con Matrices en R](https://r-coder.com/operaciones-matrices-r/) en un archivo RMarkdown (.Rmd) y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final escriba sus propias conclusiones.
  
      *Parte 4. Métodos cualitativos para el Análisis de decisiones*. Considere el siguiente video sobre *[Métodos Cualitativos para el Análisis de Decisiones](https://www.youtube.com/watch?v=Vz2Uiy67cm0)* y, a partir de lo que aprendió en las primeras partes, conviértalo en un archivo RMarkdown (.Rmd) con la receta de la solución y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final escriba sus propias conclusiones.  
  
      *Parte 5. Método del Valor Esperado*. Considere el siguiente video sobre *[Metodo del Valor Esperado para el Análisis de Decisiones](https://www.youtube.com/watch?v=d2D8aUZHAWs)* y, a partir de lo que aprendió en las primeras partes, conviértalo en un archivo RMarkdown (.Rmd) con la receta de la solución y genere un archivo HTML con *knit*. Para cada ejercicio, agregue un ejemplo adicional. Al final escriba sus propias conclusiones.
    
      Suba los archivos de la práctica a su cuenta de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.  
  
      Saque sus conclusiones y documente en un video la realización de la tarea y su experiencia en la realización de la actividad, a modo de tutorial, y comparta el video en el grupo de Telegram. Suba los archivos creados o modificados a su cuenta de Google Drive donde corresponda.  

    - *Tarea 3.2*: *Fundamentos del análisis de decisiones*. (Fecha de entrega: 17 de abril de 2022).  

      *Objetivo*: Aprender los fundamentos del análisis de decisiones.  

      Resuelva el siguiente [cuestionario](https://github.com/jzavalar/2211092-Analisis_de_Decisiones/blob/main/Unidad%203.%20Cuestionario.md) sobre los *fundamentos del análisis de decisiones*.
  
    - *Práctica 3.3. Manipulación de datos con R*. (Fecha de entrega: 24 de abril de 2022).  

      *Objetivo*: Aprender la limpieza y manipulación de datos con R para el análisis de datos.  

      *Parte 0*: Organícense en parejas.  
  
      *Parte 1*: Estudie la [Transformación de datos](https://es.r4ds.hadley.nz/transform.html#transformaciones-agrupadas-y-filtros) y resuelva los [ejercicios respectivos](https://es.r4ds.hadley.nz/transform.html#transformaciones-agrupadas-y-filtros) mediante la elaboración de un archivo RMarkdown.  

      *Parte 2*: Estudie los principios de la [Ordenación de datos](https://es.r4ds.hadley.nz/datos-ordenados.html) con el paquete *tidyverse* y resuelva los ejercicios del capítulo (12.2.1, 12.3.3, 12.4.3, 12.5.1, 12.6.1) mediante la elaboración de un archivo RMarkdown.  

      Suban los archivos de la práctica, creados o modificados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.  
  
      Saquen sus conclusiones y documenten en un video la realización de la práctica y su experiencia en la realización de la actividad, a modo de tutorial y compartan el video en el grupo de Telegram.

    - *Práctica 3.4. Manipulación de datos relacionales con R*. (Fecha de entrega: 24 de abril de 2022).  

      *Objetivo*: Aprender la manipulación de datos relacionales con R, como aproximación a las bases de datos relacionales.  

      *Parte 0*: Organícense en parejas.  
  
      *Parte 1*: Prerrequisitos: Debe haber realizado las primeras dos partes de esta práctica y haber resuelto la *Tarea 2.1: Teoría de las bases de datos relacionales*.  
  
      *Parte 2*: Estudie los principios de manejo de [Datos relacionales](https://es.r4ds.hadley.nz/datos-relacionales.html) y resuelva los ejercicio del capítulo (13.2.1, 13.3.1, 13.4.6, 13.5.1) mediante la elaboración de un archivo RMarkdown.  

      Suban los archivos de la práctica, creados o modificados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.  
  
      Saquen sus conclusiones y documenten en un video la realización de la práctica y su experiencia en la realización de la actividad, a modo de tutorial y compartan el video en el grupo de Telegram.

    - *Práctica 3.5. Optimización con R*. (Fecha de entrega: Ninguna, pues es opcional).  

      *Objetivo*: Aprender el procedimiento general de resolución de problemas de programación lineal con R.  

      *Parte 0*: Organícense en parejas.  
  
      *Parte 1*: Repase la teoría de optimización matemática de la *programación lineal* usando R en este tutorial-ejemplo de *Optimización en R* de [Chung (2020, Jun 23)](https://rpubs.com/vchung/programacion), en este otro tutorial sobre *Optimización Lineal con R* de [Berrendero (2015)](https://caminosaleatorios.files.wordpress.com/2015/03/optimizacion-lineal-r.pdf) y el tutorial sobre *Calculadoras de Optimización* o (*Solvers*) de [Palomar (2020)](https://palomar.home.ece.ust.hk/MAFS6010R_lectures/Rsession_solvers.html), donde también encontrará soluciones para otras técnicas como *mínimos cuadrados*, *programación entera*, *programación cuadrática* y *programación mixta*, entre otros. 
  
      *Parte 2*: Aparte de los paquetes [lpSolve](https://cran.r-project.org/web/packages/lpSolve/index.html) y [lpSolveAPI](https://cran.r-project.org/web/packages/lpSolveAPI/index.html), es de particular interés el paquete [R Optimization Infrastructure (ROI)](https://roi.r-forge.r-project.org/) porque es la solución de optimización más completa disponible actualmente en R. 
  
      *Parte 3*: Enfóquese en aprender:   
          a. A utilizar la codificación en LaTEX para escribir ecuaciones, matrices y símbolos matemáticos (ver [Editor Online](https://latex.codecogs.com/eqneditor/editor.php)),  
          b. La codificación de vectores y matrices para reolver los problemas de optimización con los paquetes *lpSolve*, *lpSolveAPI* y *ROI* de R con RStudio,  
          c. La graficación simple con R apoyándose en el tutorial de [Alegre Ordoñez (2019, Mar 7)](http://rstudio-pubs-static.s3.amazonaws.com/474421_3dfcb62391eb4ac495a863dea86121d9.html), y  
          d. Reproduzcan los ejercicios respectivos, comprobando la validez y documenten el algoritmo en una compilación en un archivo *RMarkdown*.  

      *Parte 4*: Explore y exponga algunos de los problemas representativos de su carrera que podría resolver utilizando estas técnicas y saquen sus conclusiones.   

      Suban los archivos de la práctica, creados o modificados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.  
  
      Documenten en un video la realización de la práctica y su experiencia en la realización de la actividad, a modo de tutorial y compartan el video en el grupo de Telegram.


#### Unidad 3. Los problemas de decisión
1. Modelación de los problemas de decisión
2. Proceso de resolución de problemas de decisión
3. Estructuración de problemas de decisión
4. La situación a analizar
5. Modelos de decisión: 
   - Matriz de pagos
   - Árboles de decisión
   - Modelo de scoring
   - Modelo de norma mínima
   - Otras técnicas
6. Tareas y prácticas
   - *Tarea 4.1*: *Fundamentos de la estructuración de problemas de decisión*. (Fecha de entrega: 11 de mayo de 2022).  

     *Objetivo*: Aprender los fundamentos de la estructuración de problemas de decisión.  

     *Parte 0*: Organícense en parejas.  
  
     *Parte 1*: Resuelva el siguiente [cuestionario](https://github.com/jzavalar/2211092-Analisis_de_Decisiones/blob/main/Unidad%204.%20Cuestionario.md) sobre la *estructuración de los problemas de decisión*, mediante la elaboración de un archivo RMarkdown.  
 
     Saquen sus conclusiones y suban los archivos creados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la tarea.

   - *Práctica 4.2*: *Instalación y uso básico de Radiant, análitica de negocios con R y Shiny*. (Fecha de entrega: 11 de mayo de 2022).    
      
     *Objetivo*: Instalar y usar *Radiant* para el análisis de negocios con *R* y *Shiny* en *RStudio*.    
      
     *Parte 1*: Instale el plugin [Radiant](https://cran.r-project.org/web/packages/radiant.data/readme/README.html), de acuerdo a las [instrucciones](https://radiant-rstats.github.io/docs/index.html), en su instalación de *RStudio*.  
      
     *Parte 2*: *Instrucciones generales*. Estudie el tema de *Análisis de Decisiones* usando *árboles de decisión* en el [tutorial escrito](https://radiant-rstats.github.io/docs/model/dtree.html) de *Radiant* y en la [lista de reproducción](https://www.youtube.com/watch?v=plSeVJ7c-Iw&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw) correspondiente. 
      
     Utilice el [tutorial escrito](https://radiant-rstats.github.io/docs/model/dtree.html) como base para la generación del archivo *RMarkdown* que contenga las recetas correspondientes en español. Este será un entregable. 
      
     Además, utilice los [archivos YAML](https://uc2a9e31d90010cc1bfd4229da2a.dl.dropboxusercontent.com/zip_download_get/BH8yEm5Fx3j6a7es51fpAxNGw4eiKdA41uC8yYW-Voo8Gzh05VpCnCTEiQpyPTdSgDj0IoIkw-x-63Z0xmYavHUiFmBOtGHfr9g2Y95nrB7YQA?dl=1#) de los ejercicios como insumos, introduzca los comentarios respectivos en el archivo YAML (con # igual que en R) y traduzca lo que corresponda. Estos archivos serán sus otros entregables. 
      
     Una vez que haga la simulación con los árboles de decisión inicial y final, guarde sus resultados en el archivo RMarkdown.
   
     *Parte 3:* Estudie los primeros tres videos en la [lista de reproducción](https://www.youtube.com/watch?v=plSeVJ7c-Iw&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw) correspondiente y reproduzca los dos ejercicios (#1 y #2) que se muestran en los videos y genere el archivo *RMarkdown* traducido al español y haga su video de evidencia.  
      
     *Parte 4*: Estudie el tema del *análisis de sensibilidad* en *árboles de decisión* en el video 4 de la [lista de reproducción](https://www.youtube.com/watch?v=c_pCCCn6FEw&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=4) correspondiente. Reproduzca el  ejercicio #3 que se muestra en el video y genere la parte correspondiente del archivo *RMarkdown* en español y haga su video de evidencia.  
      
     *Parte 5*: Estudie la depuración de los errores de la entrada de datos en *árboles de decisión* en el video 5 de la [lista de reproducción](https://www.youtube.com/watch?v=oiwv15bbjzs&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=5) correspondiente.  Reproduzca el ejercicio #4 que se muestra en el video y genere el archivo *RMarkdown* con su informe en español y haga el video correspondiente.  
      
     *Parte 6*: Estudie el tema de probabilidad en *árboles de decisión* en el video 6 de la [lista de reproducción](https://www.youtube.com/watch?v=xuv9zgAcvCQ&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=6) correspondiente. Reproduzca el  ejercicio #3 que se muestra en el video y genere el archivo *RMarkdown* con su informe en español y haga el video correspondiente.
      
     *Parte 7*: Estudie el tema de *árboles de decisión* con información imperfecta en el video 7 de la [lista de reproducción](https://www.youtube.com/watch?v=xuv9zgAcvCQ&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=7) correspondiente. Reproduzca el  ejercicio #4 que se muestra en el video y genere el archivo *RMarkdown* con su informe en español y haga el video correspondiente.
      
     *Parte 8*: Aprenda a desarrollar los *árboles de decisión* con información imperfecta en el video 8 de la [lista de reproducción](https://www.youtube.com/watch?v=xuv9zgAcvCQ&list=PLNhtaetb48EdKRIY7MewCyvb_1x7dV3xw&index=8) correspondiente. Reproduzca el  ejercicio #2 que se muestra en el video y genere el archivo *RMarkdown* con su informe en español y haga el video correspondiente.
      
     Saquen sus conclusiones y suban los archivos creados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la práctica.

   - *Práctica 4.3*: *Las decisiones grupales: Un enfoque deontológico*. (Fecha de entrega: 16 de mayo de 2022 a las 24:00 hr, 1 punto extra en la Unidad 4, a quien lo realice).    
      
     *Objetivo*: Comprender la complejidad de la toma de decisiones grupales y la importancia de la ética.    
      
     Desarrolle la siguiente [actividad](https://github.com/jzavalar/2211092-Analisis_de_Decisiones/blob/main/Unidad_4._Practica_4.3.md).  
 
     Saquen sus conclusiones y suban los archivos creados, a sus cuentas de *Google Drive*, en la carpeta respectiva, con el nombre de la tarea.




### Bibliografía General:

- Recursos digitales en la UAM: biblioteca de la Unidad Iztapalapa ([url](http://contingencia.izt.uam.mx/wp-content/uploads/2020/04/Biblioteca-Nuevo-3b-bindani-B.pdf)), biblioteca digital ([url](https://bidi.uam.mx/index.html)), [recursos varios](http://pcyti.izt.uam.mx/recursos/infext/infoext.html).  
- Recursos controversiales: [Library Genesis](http://gen.lib.rus.ec/) (libros, artículos, novelas), [**SciHub**](https://sci-hub.se/about) (artículos), [The Pirate Bay](https://thepiratebay.org/index.html) (P2P file sharing network) (archivos), [Academic Torrents](http://academictorrents.com/) (artículos, datos y cursos).
- Repositorios de software: [Software para la comunidad UAM](https://www.uam.mx/ti/soft/), [AlternativeTo](https://alternativeto.net/), [SourceForge](https://sourceforge.net/), [CDLibre](https://www.cdlibre.org/), [Software Heritage](https://www.softwareheritage.org/?lang=es), [GitHub](https://github.com/github).
- Hernández, L. (2012, Nov 16). **El Software Libre y la educación** por Richard Stallman. *YouTube* ([url](https://www.youtube.com/watch?v=aRvorE9PJso)).  
- Valcheva, S. (s.f.). 10 Open Source Decision Tree Software Tools. ([url](https://www.intellspot.com/open-source-decision-tree/)).

- Universitat de les Illes Balears. Som UIB (2016, Sep 22). MOOC Aprende R : Introducción al tratamiento de datos con R y RStudio. *YouTube*. ([Lista de videos](https://www.youtube.com/playlist?list=PLnXFIHWLWQXFOIOdpAv2ioBHQuYgV7x2t)).
- Wickham, H. & Grolemund, G. (2017). *R for data science: Import, tidy, transform, visualize, and model data*. O'Reilly. ([url](https://r4ds.had.co.nz/)). (R para ciencia de datos, [traducción español](https://r4ds-en-espaniol.netlify.app/)). (Solución de los ejercicios, [url](https://cienciadedatos.github.io/r4ds-soluciones/index.html)).
- Teetor, P. (2019). *R cookbook: Proven recipes for data analysis, statistics, and graphics*. O'Reilly. [Online] ([url](https://rc2e.com/)). ([traducción al español](https://translate.google.com/translate?sl=en&tl=es&u=https://rc2e.com/)).
- Wickham, H. & Grolemund, G. (2017). R for data science. [Online] ([url](https://r4ds.had.co.nz/)), [traducción al español] ([url](https://es.r4ds.hadley.nz/)).
- RStudio cheatsheets. ([url](https://github.com/rstudio/cheatsheets)).

## Modalidades de Evaluación

### Evaluación Global
La asistencia puntual a la clase es obligatoria, según el reglamento de estudios. Es importante la *participación activa clase a clase*. La falta de participación en clase y la no entrega de sus reportes de prácticas a lo largo del trimestre, tendrá repercusiones en la evaluación final que puede llegar a la reprobación del curso. Ver porcentajes de ponderación de calificación.

#### Calificación
| Factor | Porcentaje | Observaciones |
| --- | :---: | ------------- |
| Tareas|30% |Se entrega en la fecha programada |
| Prácticas| 30% |Se entregan  en la fecha programada |
| Exámenes| 40% | Primero (a), Segundo (b)|
| Total | 100% | |

**Notas:
  - **a).** Primer examen: *Teórico* (Unidades ) y *Práctico* (): Fecha: 
  - **b).** Segundo examen: *Teórico - Práctico* (Unidad 4): Fecha: 
  - **Evaluación Global:** Todo el curso (Teoría y Práctica) para quienes tengan baja calificación o deseen subir.
  - **Entrega de calificaciones:** .

La *evaluación final* será un examen teórico-práctico que versará sobre la totalidad de las unidades. 

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
