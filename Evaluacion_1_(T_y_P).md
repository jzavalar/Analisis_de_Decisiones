4 Ejercicios evaluables

Ejercicio 1: Resuelve dos PPLs de la lista a continuación, por duplicado (usando ambas funciones de R para cada PPL), clasificando el PPL y comentando el resultado:

    Solución óptima: justificar, decir la solución óptima y valor de la función objetivo,
    Problema no acotado, justificar,
    Problema infactible, justificar.

Para escoger los 2 PPLs aleatoriamente, ejecuta la siguiente instrucción y resuelve los que resulten en la simulación:

# primero cambia eval=TRUE en la línea superior
set.seed(20170505) # cambia por tu fecha de cumpleaños
sample(x=1:6, size=2)

ENUNCIADOS:
$$
\(\left\{\begin{array}{rl} \text{max} &amp;x_1 -2x_2 -3x_3 -x_4\\ 
\text{s.a} &amp; \\ &amp; x_1 - x_2 - 2x_3 - x_4 \leq 4 \\ &amp; 2x_1 + x_3 - 4x_4 \leq 2 \\ &amp; -2x_1 + x_2 + x_4 \leq 1 \\ &amp; x_1, x_2, x_3, x_4 \geq 0 \end{array} \right.\)
$$


# AQUÍ EL CÓDIGO

Y AQUÍ LOS COMENTARIOS SOBRE LA SOLUCIÓN QUE TE HA DADO

    ⎧⎩⎨⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪mins.a3y1−y2+2y32y1−y2+y3≥−1y1+2y3≥2−7y1+4y2−6y3≥1y1,y2,y3≥0

# AQUÍ EL CÓDIGO

Y AQUÍ LOS COMENTARIOS SOBRE LA SOLUCIÓN QUE TE HA DADO

    ⎧⎩⎨⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪maxs.a−x1−x2+2x3−3x1+3x2+x3≤32x1−x2−2x3≤1−x1+x3≤1x1,x2,x3≥0

# AQUÍ EL CÓDIGO

Y AQUÍ LOS COMENTARIOS SOBRE LA SOLUCIÓN QUE TE HA DADO

    ⎧⎩⎨⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪mins.a5y1−2y2−y3−2y1+3y3≥−12y1−y2+y3≥13y1+2y2−y3≥0y1,y2,y3≥0

# AQUÍ EL CÓDIGO

Y AQUÍ LOS COMENTARIOS SOBRE LA SOLUCIÓN QUE TE HA DADO

    ⎧⎩⎨⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪mins.a−2y2+y3−y1−2y2≥−34y1+y2+7y3≥−12y1−3y2+y3≥−5y1,y2,y3≥0

# AQUÍ EL CÓDIGO

Y AQUÍ LOS COMENTARIOS SOBRE LA SOLUCIÓN QUE TE HA DADO

    ⎧⎩⎨⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪maxs.a3x1+4x2+5x3x1+2x2+2x3≤1−3x1+x3≤−1−2x1−x2≤−1x1,x2,x3≥0

# AQUÍ EL CÓDIGO

Y AQUÍ LOS COMENTARIOS SOBRE LA SOLUCIÓN QUE TE HA DADO
