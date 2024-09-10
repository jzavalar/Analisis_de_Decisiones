# Problema 1. Perforación de un pozo para extraer gas natural

## Planteamiento del problema

Una gran compañía de energéticos ofrece al dueño de un terreno $60,000 dólares por los derechos de exploración de gas natural en un sitio determinado y la opción para un desarrollo futuro. La opción, si se ejerce, vale $60,000 adicionales para el propietario, pero esto ocurrirá sólo si se descubre gas natural durante la etapa de exploración. El propietario, considerando que el interés de la compañía es una buena indicación de que existe gas, está tentado a desarrollar él mismo el campo. Para hacer esto, deberá contratar equipos locales con experiencia en exploración y desarrollo. El costo inicial es de $100,000, los que se perderán si no se encuentra gas. Sin embargo, si descubre gas, el propietario estima un beneficio neto de 2 millones de dólares.

A continuación voy a mostrar el uso de [*ChatGPT*](https://chatgpt.com/) como una herramienta poderosa para el estudio de esta UEA, al considerarla como un tutor universal. Destacaré el *prompt* y la *respuesta*:

## 1. Planteamiento del Problema

En este primer prompt se solicita que, a partir del texto del problema, se realice el encuadre del problema.

### Prompt
Te voy a dar un problema para que me ayudes con la realización de varios análisis desde la perspectiva de la teoría de decisiones (análisis de decisiones) de la investigación de operaciones. El texto del problema es el siguiente:  

"Una gran compañía de energéticos ofrece al dueño de un terreno $60,000 dólares por los derechos de exploración de gas natural en un sitio determinado y la opción para un desarrollo futuro. La opción, si se ejerce, vale $60,000 adicionales para el propietario, pero esto ocurrirá sólo si se descubre gas natural durante la etapa de exploración. El propietario, considerando que el interés de la compañía es una buena indicación de que existe gas, está tentado a desarrollar él mismo el campo. Para hacer esto, deberá contratar equipos locales con experiencia en exploración y desarrollo. El costo inicial es de $100,000, los que se perderán si no se encuentra gas. Sin embargo, si descubre gas, el propietario estima un beneficio neto de 2 millones de dólares." 

El primer análisis que debes hacer es el "Encuadre del problema", que consiste en identificar en el texto del problema: a) El Decisor, b) Las acciones o decisiones posibles, c) Los estados de la naturaleza y d) La función de consecuencias o matriz de pagos. Abunda brevemente exponiendo los conceptos involucrados. Modifica tu propuesta nombrando las acciones como $a_1$, $a_2$, etc. y los estados de la naturaleza como $\theta_1$, $\theta_2$, etc. 

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

### Explicación
- Si el propietario toma la acción $a_1$ (aceptar la oferta de la compañía) y ocurre el estado $\theta_1$ (hay gas), recibe $60,000 por los derechos de exploración y $60,000 adicionales, sumando $120,000.
- Si toma la acción $a_1$ y ocurre el estado $\theta_2$ (no hay gas), recibe únicamente $60,000.
- Si el propietario toma la acción $a_2$ (desarrollar él mismo el campo) y ocurre el estado $\theta_1$ (hay gas), obtiene $2 millones de dólares, menos el costo de $100,000, lo que da una ganancia neta de $1,900,000.
- Si toma la acción $a_2$ y ocurre el estado $\theta_2$ (no hay gas), pierde los $100,000 invertidos.

### Resumen
- **Decisor**: Es el individuo o la entidad que toma una decisión basada en las consecuencias esperadas de sus posibles acciones.
- **Acciones** ($a_1$, $a_2$): Son las alternativas disponibles para el decisor, cada una de las cuales conduce a resultados diferentes dependiendo del estado de la naturaleza.
- **Estados de la naturaleza** ($\theta_1$, $\theta_2$): Son factores externos que afectan el resultado de una decisión, pero que están fuera del control del decisor. En este caso, $\theta_1$ indica que hay gas y $\theta_2$ indica que no hay gas.
- **Función de consecuencias**: Es la relación que asigna un resultado o beneficio esperado (normalmente expresado en términos monetarios) a cada combinación de acción y estado de la naturaleza.

Este es el primer paso del análisis de decisiones, que consiste en enmarcar el problema para clarificar los componentes clave antes de proceder con los cálculos de valor esperado, entre otros.

## 3. Análisis de decisiones bajo *completa incertidumbre*

### Prompt
A continuación, realiza el "análisis de decisiones bajo completa incertidumbre". Para ello, utiliza los siguientes "criterios de elección no probabilísticos": a) Criterio maximin de Wald, b) Criterio maximax, c) Criterio de Hurwicz y d) Pesar minimax o Criterio de Savage. En el análisis del criterio de Hurwicz contrasta el análisis< con el índice $\alpha$ en los tres escenarios posibles: pesimista (0 menor o igual a $\alpha$ menor a 0.5), neutro ($\alpha$ igual a 0.5), optimista (0.5 menor a $\alpha$ menor o igual a 1). En el análisis del criterio de Savage incluye la matriz de pérdida de oportunidad. Desarrolla tu respuesta con los conceptos involucrados y el razonamiento que hay detrás de cada criterio, seguido del algoritmo básico y la elección. Haz una exposición didáctica y breve, pero suficiente para comprender cabalmente cada criterio.

### Respuesta
Este análisis utiliza varios **criterios de elección no probabilísticos** para tomar una decisión bajo incertidumbre completa. El problema plantea una situación en la que el decisor no conoce las probabilidades de los estados de la naturaleza, por lo que debe basarse en criterios alternativos.

#### Matriz de Pagos

| **Decisiones/Estados de la Naturaleza** | **$\theta_1$ (Hay gas)**    | **$\theta_2$ (No hay gas)**  |
|-----------------------------------------|-----------------------------|------------------------------|
| **Acción $a_1$ (Aceptar oferta)**       | $120,000                    | $60,000                      |
| **Acción $a_2$ (Desarrollar el campo)** | $1,900,000                  | -$100,000                    |

### 3.a. Criterio Maximin (de Wald)

El **criterio maximin** es conservador o **pesimista**. El decisor selecciona la acción cuyo peor resultado es el mejor posible.

- **Acción $a_1$ (Aceptar oferta)**: El peor resultado es $60,000.
- **Acción $a_2$ (Desarrollar el campo)**: El peor resultado es -$100,000.

**Elección**: Según este criterio, se elige la **acción $a_1$ (aceptar la oferta)**, ya que $60,000 es mejor que -$100,000.

### 3.b. Criterio Maximax

El **criterio maximax** es **optimista**. Se elige la acción que tiene el mejor resultado máximo posible.

- **Acción $a_1$ (Aceptar oferta)**: El mejor resultado es $120,000.
- **Acción $a_2$ (Desarrollar el campo)**: El mejor resultado es $1,900,000.

**Elección**: Según este criterio, se elige la **acción $a_2$ (desarrollar el campo)**, ya que $1,900,000 es el máximo valor posible.

### 3.c. Criterio de Hurwicz

El **criterio de Hurwicz** es un compromiso entre el pesimismo y el optimismo, ponderando los mejores y peores resultados con un coeficiente $\alpha$ que refleja el nivel de optimismo (0 ≤ $\alpha$ ≤ 1).

La fórmula es:   
$\text{Valor Hurwicz} = \alpha \times (\text{máximo pago}) + (1-\alpha) \times (\text{mínimo pago})$

#### Escenario pesimista ($\alpha < 0.5$)
Supongamos $\alpha = 0.3$ (más pesimista).

- **Acción $a_1$**:  
  $H(a_1) = 0.3 \times 120,000 + 0.7 \times 60,000 = 36,000 + 42,000 = 78,000$
    
- **Acción $a_2$**:  
  $H(a_2) = 0.3 \times 1,900,000 + 0.7 \times (-100,000) = 570,000 - 70,000 = 500,000$  

**Elección**: Para $\alpha = 0.3$, se elige **$a_2$ (desarrollar el campo)**.

#### Escenario neutro ($\alpha = 0.5$)
Si $\alpha = 0.5$, el decisor es neutral.

- **Acción $a_1$**:  
  $H(a_1) = 0.5 \times 120,000 + 0.5 \times 60,000 = 60,000 + 30,000 = 90,000$

- **Acción $a_2$**:  
  $H(a_2) = 0.5 \times 1,900,000 + 0.5 \times (-100,000) = 950,000 - 50,000 = 900,000$

**Elección**: Para $\alpha = 0.5$, se elige **$a_2$ (desarrollar el campo)**.

#### Escenario optimista ($\alpha > 0.5$)
Supongamos $\alpha = 0.7$ (más optimista).

- **Acción $a_1$**:  
  $H(a_1) = 0.7 \times 120,000 + 0.3 \times 60,000 = 84,000 + 18,000 = 102,000$
  
- **Acción $a_2$**:  
  $H(a_2) = 0.7 \times 1,900,000 + 0.3 \times (-100,000) = 1,330,000 - 30,000 = 1,300,000$

**Elección**: Para $\alpha = 0.7$, se elige **$a_2$ (desarrollar el campo)**.

#### Conclusión del criterio de Hurwicz
Independientemente del valor de $\alpha$, se elige **$a_2$ (desarrollar el campo)**, ya que pondera mejor los resultados máximos.

### 3.d. Criterio de Savage (Pesar Minimax)

El **criterio de Savage** busca minimizar la "pérdida de oportunidad" o "regret". Primero, construimos la **matriz de pérdida de oportunidad**.

**Matriz de pérdida de oportunidad**

| **Decisiones/Estados de la Naturaleza** | **$\theta_1$ (Hay gas)**    | **$\theta_2$ (No hay gas)**  |
|-----------------------------------------|-----------------------------|------------------------------|
| **Acción $a_1$ (Aceptar oferta)**       | $1,900,000 - 120,000 = 1,780,000 | $60,000 - 60,000 = 0              |
| **Acción $a_2$ (Desarrollar el campo)** | $1,900,000 - 1,900,000 = 0   | $60,000 - (-100,000) = 160,000 |

Matriz de pérdida de oportunidad:

| **Decisiones/Estados de la Naturaleza** | **$\theta_1$ (Hay gas)**    | **$\theta_2$ (No hay gas)**  |
|-----------------------------------------|-----------------------------|------------------------------|
| **Acción $a_1$ (Aceptar oferta)**       | $1,780,000 | $0              |
| **Acción $a_2$ (Desarrollar el campo)** | $0   | $160,000 |


**Elección según el criterio minimax**
El decisor selecciona la acción que minimiza la pérdida máxima posible.

- **Acción $a_1$**: La pérdida máxima es $1,780,000.
- **Acción $a_2$**: La pérdida máxima es $160,000.

**Elección**: Según este criterio, se elige **$a_2$ (desarrollar el campo)**, ya que su pérdida máxima es considerablemente menor.

### Conclusión General

- Según los **criterios maximin** y **Savage**, se elige la **acción $a_1$ (aceptar la oferta)**, ya que es una opción conservadora.
- Según los **criterios maximax**, **Hurwicz**, y **minimax**, se elige la **acción $a_2$ (desarrollar el campo)**, debido a la alta posibilidad de obtener un gran beneficio.

El decisor deberá elegir entre estas acciones dependiendo de su aversión al riesgo y su nivel de optimismo.

