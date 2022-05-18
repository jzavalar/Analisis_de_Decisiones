**Universidad Autónoma Metropolitana Unidad Iztapalapa**  
**UEA: 2211092 - Análisis de Decisiones**  
**Trimeste: 22-I**  

prof. dr. Jesús Zavala Ruiz  

18 de mayo de 2022  

#### Evaluación práctica global

*Instrucciones*: Resuelva los ejercicios que a continuación se indican.

- *Parte 0. Programación lineal*. Utilice RStudio y cree un ùnico archivo RMarkdown nombrado como `Apellido-Nombre_Evaluacion_practica_global_AD` que incluya sus datos personales, los datos de la UEA y la fecha. 

- *Parte 1. Selección de problemas a realizar*. Ejecute la siguiente simulación en R para que obtenga la lista de problemas que deberá resolver de la lista de problemas que se incluyen el siguiente [archivo](https://drive.google.com/file/d/1XOd8olTQY39sKb0L-3grLY38o3LoQdOF/view?usp=sharing).

```{r}
# cambie el valor de la semilla 20220427 por su fecha de cumpleaños: año-mes-dia (aaaammdd)
set.seed(20220518) 
sample(x=1:3, size=2)
```

- *Parte 2: Prepare su entorno de desarrollo* con los paquetes `lpSolve`,`Radiant` y `decisionSupport` en su entorno. Si no los tiene instalados, hágalo previamente. Cada vez que requiera cargue los paquetes necesarios.

- *Parte 3: Programación lineal*. No suponga que el lector es adivino. Así que, para cada problema, haga un informe como si fuera un tutorial, donde explique calramente el algoritmo de solución, utilizando el paquete `lpSolve`, en RStudio. 
  Para cada paso explique claramente lo que está haciendo e interprete los resultados obtenidos. 
  Una vez resuelto, responda si:
    - El problema tiene una **solución óptima**, justifique e indique la solución óptima para cada variable y el valor de la función objetivo.  
    - El problema es **no acotado**, justifique su respuesta a partir de la interpretación de la salida de las funciones.  
    - El Problema es **infactible**, justifique su respuesta a partir de la interpretación de la salida de las funciones.   

- *Parte 4: Árbol de decisiones*. Estudie los árboles de decisiones que se incluyen en la siguiente [referencia]([https://drive.google.com/file/d/1WkzDqi0hwV8_ObUys3oExHip0eiRr6Wb/view?usp=sharing](https://www.youtube.com/watch?v=MRULBcvqYus)).
  Luego, codifíquelos (estos son sus primeros entregables) y resuélvalos con `Radiant` (estos son sus segundos entregables), interprete los resultados y compárelo con la solución de la referencia. Finalmente, saque sus conclusiones.  
  Asegúsese de que su informe sea reproducible en el archivo RMarkdown. Exponga el problema y haga los cambios que permitan explicar lo suficientemente claro el algoritmo de solución. Si requiere use este [tutorial](https://radiant-rstats.github.io/docs/programming.html).
 
- *Parte 5: Entregable*. Finalmente, compile su archivo RMarkdown y genere su archivo de HTML de salida. Prepare sus entregables y envíelos a su profesor por chat privado por Telegram.  
