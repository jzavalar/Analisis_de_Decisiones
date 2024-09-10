# Problema 1. Perforación de un pozo para extraer gas natural

## Planteamiento del problema

Una gran compañía de energéticos ofrece al dueño de un terreno $60,000 dólares por los derechos de exploración de gas natural en un sitio determinado y la opción para un desarrollo futuro. La opción, si se ejerce, vale $60,000 adicionales para el propietario, pero esto ocurrirá sólo si se descubre gas natural durante la etapa de exploración. El propietario, considerando que el interés de la compañía es una buena indicación de que existe gas, está tentado a desarrollar él mismo el campo. Para hacer esto, deberá contratar equipos locales con experiencia en exploración y desarrollo. El costo inicial es de $100,000, los que se perderán si no se encuentra gas. Sin embargo, si descubre gas, el propietario estima un beneficio neto de 2 millones de dólares.

A continuación voy a mostrar el uso de *[ChatGPT][]* como una herramienta poderosa para el estudio de esta UEA, al considerarla como un tutor universal. Destacaré el *prompt* y la *respuesta*:

## 1. Planteamiento del Problema

En este primer prompt se solicita que, a partir del texto del problema, se realice el encuadre del problema.

Te voy a dar un problema para que me ayudes con la realización de varios análisis desde la perspectiva de la teoría de decisiones (análisis de decisiones) de la investigación de operaciones. El texto del problema es el siguiente:  

"Una gran compañía de energéticos ofrece al dueño de un terreno $60,000 dólares por los derechos de exploración de gas natural en un sitio determinado y la opción para un desarrollo futuro. La opción, si se ejerce, vale $60,000 adicionales para el propietario, pero esto ocurrirá sólo si se descubre gas natural durante la etapa de exploración. El propietario, considerando que el interés de la compañía es una buena indicación de que existe gas, está tentado a desarrollar él mismo el campo. Para hacer esto, deberá contratar equipos locales con experiencia en exploración y desarrollo. El costo inicial es de $100,000, los que se perderán si no se encuentra gas. Sin embargo, si descubre gas, el propietario estima un beneficio neto de 2 millones de dólares." 

El primer análisis que debes hacer es el "Encuadre del problema", que consiste en identificar en el texto del problema: a) El Decisor, b) Las acciones o decisiones posibles, c) Los estados de la naturaleza y d) La función de consecuencias o matriz de pagos. Abunda brevemente exponiendo los conceptos involucrados. Modifica tu propuesta nombrando las acciones como $a_1$, $a_2$, etc. y los estados de la naturaleza como $\theta_1$, $\theta_2$, etc. 

Respuesta:

# 2. Encuadre del Problema

Este problema puede ser enmarcado dentro del análisis de decisiones de la investigación de operaciones, utilizando la teoría de decisiones bajo incertidumbre. Vamos a descomponerlo para identificar los elementos principales:

### a) El Decisor
El **decisor** es el **propietario del terreno**. Es quien tiene que tomar una decisión sobre si aceptar la oferta de la compañía de energéticos o desarrollar él mismo el campo de gas natural.

### b) Las acciones o decisiones posibles
El propietario tiene dos posibles **acciones** o **decisiones**:

- **Acción $a_1$**: **Aceptar la oferta de la compañía de energéticos**. El propietario cede los derechos de exploración y recibe $60,000 dólares de forma segura. Además, si se descubre gas, obtendrá $60,000 adicionales.

- **Acción $a_2$**: **Desarrollar él mismo el campo**. Esto implica contratar equipos para explorar el campo con un costo inicial de $100,000 dólares. Si se encuentra gas, los beneficios serían de $2 millones de dólares, pero si no hay gas, el propietario perdería los $100,000 invertidos.

### c) Los estados de la naturaleza
Los **estados de la naturaleza** son los escenarios externos que afectan las consecuencias de las decisiones. En este caso, los estados son:

- **Estado $\theta_1$**: **Hay gas** en el terreno.
- **Estado $\theta_2$**: **No hay gas** en el terreno.

### d) Función de Consecuencias o Matriz de Pagos
La **función de consecuencias** o **matriz de pagos** describe los resultados (en términos monetarios) de cada decisión, bajo cada estado de la naturaleza.

Podemos organizarla así:

| **Decisiones/Estados de la Naturaleza** | **$\theta_1$ (Hay gas)**    | **$\theta_2$ (No hay gas)**  |
|-----------------------------------------|-----------------------------|------------------------------|
| **Acción $a_1$ (Aceptar oferta)**       | $120,000                    | $60,000                      |
| **Acción $a_2$ (Desarrollar el campo)** | $1,900,000                  | -$100,000                    |

#### Explicación:
- Si el propietario toma la acción $a_1$ (aceptar la oferta de la compañía) y ocurre el estado $\theta_1$ (hay gas), recibe $60,000 por los derechos de exploración y $60,000 adicionales, sumando $120,000.
- Si toma la acción $a_1$ y ocurre el estado $\theta_2$ (no hay gas), recibe únicamente $60,000.
- Si el propietario toma la acción $a_2$ (desarrollar él mismo el campo) y ocurre el estado $\theta_1$ (hay gas), obtiene $2 millones de dólares, menos el costo de $100,000, lo que da una ganancia neta de $1,900,000.
- Si toma la acción $a_2$ y ocurre el estado $\theta_2$ (no hay gas), pierde los $100,000 invertidos.

### Resumen de los conceptos involucrados:
- **Decisor**: Es el individuo o la entidad que toma una decisión basada en las consecuencias esperadas de sus posibles acciones.
- **Acciones** ($a_1$, $a_2$): Son las alternativas disponibles para el decisor, cada una de las cuales conduce a resultados diferentes dependiendo del estado de la naturaleza.
- **Estados de la naturaleza** ($\theta_1$, $\theta_2$): Son factores externos que afectan el resultado de una decisión, pero que están fuera del control del decisor. En este caso, $\theta_1$ indica que hay gas y $\theta_2$ indica que no hay gas.
- **Función de consecuencias**: Es la relación que asigna un resultado o beneficio esperado (normalmente expresado en términos monetarios) a cada combinación de acción y estado de la naturaleza.

Este es el primer paso del análisis de decisiones, que consiste en enmarcar el problema para clarificar los componentes clave antes de proceder con los cálculos de valor esperado, entre otros.

## 3. Análisis de decisiones bajo *completa incertidumbre*

Vamos a desarrollar el **análisis de decisiones bajo completa incertidumbre** usando diferentes **criterios de elección no probabilísticos**:

### 3.a. Criterio Maximin de Wald
El **criterio maximin** es un enfoque pesimista que selecciona la acción que maximiza el **mínimo** beneficio posible, protegiéndose contra el peor escenario.

**Algoritmo básico**:
1. Para cada acción, identifica la **mínima** ganancia posible (el peor escenario para esa acción).
2. Selecciona la acción con el **máximo** de esos mínimos.

**Aplicación**
Tomemos la matriz de pagos:

$$$
\begin{array}{|c|c|c|}
\hline
\text{Decisiones/Estados de la Naturaleza} & \theta_1 \ (\text{Hay gas}) & \theta_2 \ (\text{No hay gas}) \\
\hline
a_1 \ (\text{Aceptar oferta}) & 120,000 & 60,000 \\
a_2 \ (\text{Desarrollar el campo}) & 1,900,000 & -100,000 \\
\hline
\end{array}
$$$

- Para $a_1$, el mínimo es $60,000$.
- Para $a_2$, el mínimo es $-100,000$.

La **acción seleccionada** bajo el criterio maximin es **$a_1$** (Aceptar la oferta), ya que su peor escenario ($60,000$) es mejor que el peor escenario de $a_2$ (-$100,000$).

### 3.b. Criterio Maximax
El **criterio maximax** es un enfoque **optimista**, que selecciona la acción que maximiza el **máximo** beneficio posible, esperando el mejor resultado.

**Algoritmo básico**
1. Para cada acción, identifica la **máxima** ganancia posible (el mejor escenario para esa acción).
2. Selecciona la acción con el **máximo** de esos máximos.

**Aplicación**
- Para $a_1$, el máximo es $120,000$.
- Para $a_2$, el máximo es $1,900,000$.

La **acción seleccionada** bajo el criterio maximax es **$a_2$** (Desarrollar el campo), ya que tiene el mayor beneficio posible ($1,900,000$).

### 3.c. Criterio de Hurwicz
El **criterio de Hurwicz** es un compromiso entre el pesimismo y el optimismo. Utiliza un parámetro $\alpha$, que representa el nivel de optimismo del decisor. La fórmula pondera el mejor y el peor resultado de cada acción:

$$$
H(a_i) = \alpha \times \text{máximo de } a_i + (1 - \alpha) \times \text{mínimo de } a_i
$$$

- Si $\alpha = 1$, es completamente optimista (equivalente al criterio maximax).
- Si $\alpha = 0$, es completamente pesimista (equivalente al criterio maximin).

**Aplicación**
Para $a_1$: 
$$$
H(a_1) = \alpha \times 120,000 + (1 - \alpha) \times 60,000
$$$
Para $a_2$: 
$$$
H(a_2) = \alpha \times 1,900,000 + (1 - \alpha) \times (-100,000)
$$$

Ahora evaluamos con diferentes valores de $\alpha$:

1. **Pesimista** ($0 \leq \alpha < 0.5$): Tomemos $\alpha = 0.3$.
   $$$
   H(a_1) = 0.3 \times 120,000 + 0.7 \times 60,000 = 36,000 + 42,000 = 78,000 \
   H(a_2) = 0.3 \times 1,900,000 + 0.7 \times (-100,000) = 570,000 - 70,000 = 500,000
   $$$
   Aquí se selecciona **$a_2$** (Desarrollar el campo).

2. **Neutro** ($\alpha = 0.5$):
   $$$
   H(a_1) = 0.5 \times 120,000 + 0.5 \times 60,000 = 60,000 + 30,000 = 90,000 \
   H(a_2) = 0.5 \times 1,900,000 + 0.5 \times (-100,000) = 950,000 - 50,000 = 900,000
   $$$
   Aquí se selecciona **$a_2$** (Desarrollar el campo).

3. **Optimista** ($0.5 < \alpha \leq 1$): Tomemos $\alpha = 0.7$.
   $$$
   H(a_1) = 0.7 \times 120,000 + 0.3 \times 60,000 = 84,000 + 18,000 = 102,000 \
   H(a_2) = 0.7 \times 1,900,000 + 0.3 \times (-100,000) = 1,330,000 - 30,000 = 1,300,000
   $$$
   Aquí se selecciona **$a_2$** (Desarrollar el campo).

**Explicación de $\alpha$**
- **Pesimista**: Con $\alpha$ bajo ($0 \leq \alpha < 0.5$), se da más peso al peor escenario.
- **Neutro**: Con $\alpha = 0.5$, se ponderan igualmente los mejores y peores escenarios.
- **Optimista**: Con $\alpha$ alto ($0.5 < \alpha \leq 1$), se da más peso al mejor escenario.

### 3.d. Criterio Minimax de Savage
El **criterio minimax** de **Savage** minimiza el **remordimiento** o la **pérdida de oportunidad**. Este criterio considera cuánto se perdería en comparación con la mejor decisión posible en cada estado de la naturaleza.

**Algoritmo básico**
1. Construir la **matriz de pérdida de oportunidad** restando el pago de cada acción del mejor pago en cada estado de la naturaleza.
2. Identificar el **máximo** valor de pérdida de oportunidad para cada acción.
3. Seleccionar la acción con el **mínimo** de esos máximos.

**Matriz de pérdida de oportunidad**
Calculamos los máximos por estado:
- En $\theta_1$ (Hay gas), el máximo es $1,900,000$.
- En $\theta_2$ (No hay gas), el máximo es $60,000$.

Ahora restamos estos valores de los pagos:

$$$
\begin{array}{|c|c|c|}
\hline
\text{Decisiones/Estados de la Naturaleza} & \theta_1 \ (\text{Hay gas}) & \theta_2 \ (\text{No hay gas}) \\
\hline
a_1 \ (\text{Aceptar oferta}) & 1,900,000 - 120,000 = 1,780,000 & 60,000 - 60,000 = 0 \\
a_2 \ (\text{Desarrollar el campo}) & 1,900,000 - 1,900,000 = 0 & 60,000 - (-100,000) = 160,000 \\
\hline
\end{array}
$$$

**Selección de la acción**
- Para $a_1$, la pérdida máxima es $1,780,000$.
- Para $a_2$, la pérdida máxima es $160,000$.

La **acción seleccionada** bajo el criterio minimax es **$a_2$** (Desarrollar el campo), ya que minimiza la pérdida de oportunidad.

---

### Resumen de Decisiones por Criterio
- **Maximin de Wald**: $a_1$ (Aceptar la oferta).
- **Maximax**: $a_2$ (Desarrollar el campo).
- **Hurwicz**: Depende de $\alpha$ (para $\alpha = 0.3$, $\alpha = 0.5$, y $\alpha = 0.7$, se selecciona $a_2$).
- **Minimax de Savage**: $a_2$ (Desarrollar el campo).

