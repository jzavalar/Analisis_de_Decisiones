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

El **criterio de Hurwicz** es un compromiso entre el pesimismo y el optimismo, ponderando los mejores y peores resultados con un coeficiente $\alpha$ que refleja el nivel de optimismo ($0 \leq \alpha \leq 1$).

La fórmula es:   

$\text{Valor Hurwicz} = \alpha \times (\text{máximo pago}) + (1-\alpha) \times (\text{mínimo pago})$

#### Escenario pesimista ($\alpha < 0.5$)
Supongamos $\alpha = 0.3$ (más pesimista).

- **Acción $a_1$**:  
  $H(a_1) = 0.3 \times \$120,000 + 0.7 \times \$60,000 = \$36,000 + \$42,000 = \$78,000$
    
- **Acción $a_2$**:  
  $H(a_2) = 0.3 \times \$1,900,000 + 0.7 \times (-\$100,000) = \$570,000 - \$70,000 = \$500,000$  

**Elección**: Para $\alpha = 0.3$, se elige **$a_2$ (desarrollar el campo)**.

#### Escenario neutro ($\alpha = 0.5$)
Si $\alpha = 0.5$, el decisor es neutral.

- **Acción $a_1$**:  
  $H(a_1) = 0.5 \times \$120,000 + 0.5 \times \$60,000 = \$60,000 + \$30,000 = \$90,000$

- **Acción $a_2$**:  
  $H(a_2) = 0.5 \times \$1,900,000 + 0.5 \times (-\$100,000) = \$950,000 - \$50,000 = \$900,000$

**Elección**: Para $\alpha = 0.5$, se elige **$a_2$ (desarrollar el campo)**.

#### Escenario optimista ($\alpha > 0.5$)
Supongamos $\alpha = 0.7$ (más optimista).

- **Acción $a_1$**:  
  $H(a_1) = 0.7 \times \$120,000 + 0.3 \times \$60,000 = \$84,000 + \$18,000 = \$102,000$  
  
- **Acción $a_2$**:  
  $H(a_2) = 0.7 \times \$1,900,000 + 0.3 \times (-\$100,000) = \$1,330,000 - \$30,000 = \$1,300,000$  

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

## 4. Análisis de decisiones bajo riesgo sin experimentación

A continuación, a partir de la matriz de pagos, realiza el "análisis bajo riesgo" de la "toma de decisiones sin experimentación", bajo los siguientes criterios: a. Criterio de Laplace, b. Criterio de la máxima posibilidad, c. Regla de decisión de Bayes (Valor Esperado Medio, VEM) y d. Minimización de la pérdida de oportunidad esperada (POE). Desarrolla tu respuesta con los conceptos involucrados y el razonamiento que hay detrás de cada criterio, seguido del algoritmo básico para su solución y la elección elegida. Haz una exposición didáctica y breve, pero suficiente, para comprender cabalmente cada criterio. En segundo lugar, codifica la respuesta en markdown compatible al 100% para publicarlo en GitHub.

### Matriz de Pagos

| **Decisiones/Estados de la Naturaleza** | **$\theta_1$ (Hay gas)**    | **$\theta_2$ (No hay gas)**  |
|-----------------------------------------|-----------------------------|------------------------------|
| **Acción $a_1$ (Aceptar oferta)**       | $120,000                    | $60,000                      |
| **Acción $a_2$ (Desarrollar el campo)** | $1,900,000                  | -$100,000                    |

### 4.a. Criterio de Laplace

El **criterio de Laplace** asume equiprobabilidad entre los estados. Calculamos el valor esperado (VE) de cada acción:

- **Acción $a_1$ (Aceptar oferta)**:
  $VE(a_1) = \frac{1}{2} \times (\$120,000 + \$60,000) = \$90,000$

- **Acción $a_2$ (Desarrollar el campo)**:
  $VE(a_2) = \frac{1}{2} \times (\$1,900,000 + (-\$100,000)) = \$900,000$

**Elección**: Se elige la **acción $a_2$ (desarrollar el campo)**.

### 4.b. Criterio de la Máxima Posibilidad

Este criterio selecciona la acción con el mejor pago en el estado más probable. Si **$\theta_1$** (hay gas) es más probable:

- **Acción $a_2$ (desarrollar el campo)** es la elección con el mejor resultado.

**Elección**: Se elige la **acción $a_2$ (desarrollar el campo)**.

### 4.c. Regla de Bayes

Criterio de la Regla de Bayes o del Valor Esperado Medio (VEM). El valor esperado se calcula ponderando los pagos con las probabilidades. Con $P(\theta_1) = p = 0.7$:

- **Acción $a_1$ (Aceptar oferta)**:
  $VE(a_1) = \$102,000$

- **Acción $a_2$ (Desarrollar el campo)**:
  $VE(a_2) = \$1,300,000$

**Elección**: Se elige la **acción $a_2$ (desarrollar el campo)**.

### 4.d. Minimización de la Pérdida de Oportunidad Esperada

Construimos la matriz de pérdida de oportunidad y calculamos la la Pérdida de Oportunidad Esperada (POE) para cada acción:

- **Acción $a_1$ (Aceptar oferta)**:  
  $POE(a_1) = \$1,246,000$
  
- **Acción $a_2$ (Desarrollar el campo)**:
  $POE(a_2) = \$48,000$

**Elección**: Se elige la **acción $a_2$ (desarrollar el campo)**.

### Conclusión General

En todos los criterios, la **acción $a_2$ (desarrollar el campo)** es la mejor opción.

## 5. Análisis básico *a posteriori* con experimentación

### Prompt
A partir de la matriz de pagos original, realiza el "análisis a posteriori" bajo la siguiente información complementaria: 
"El propietario ha decidido realizar pruebas con sonido en el sitio en donde se sospecha que haya gas natural, con un costo de $30,000. Las pruebas de sonido indican que no hay gas presente, pero la prueba no es perfecta. La compañía que realizó las pruebas acepta que 30% de las veces la prueba indicará que no hay gas cuando en realidad éste existe. Cuando no existe gas, la prueba es acertada 90% de las veces. Empleando estos datos, actualícese la estimación inicial del propietario de que la probabilidad de encontrar gas es de 0.6 y determínese después la decisión recomendada bajo el 'criterio a posteriori'."

### Respuesta

El **análisis a posteriori** implica utilizar nueva información para ajustar las probabilidades iniciales de los estados de la naturaleza. En este caso, se emplean los datos obtenidos de una prueba de sonido, que aunque no es perfecta, ayuda a actualizar la probabilidad de encontrar gas en el sitio.

### Información disponible

1. **Probabilidad inicial de encontrar gas (antes de la prueba)**:  
   $P(\theta_1) = 0.6$  
   $P(\theta_2) = 1 - P(\theta_1) = 0.4$  

2. **Información de la prueba**:
   - La prueba indicó que **no hay gas**.
   - **Tasa de error de la prueba**:
     - **Falso negativo**: $P(\text{Prueba indica no gas} | \theta_1) = 0.3$
     - **Verdadero negativo**: $P(\text{Prueba indica no gas} | \theta_2) = 0.9$

3. **Costo de la prueba**:  
   - $30,000.

## Aplicación del Teorema de Bayes

El **Teorema de Bayes** nos permite calcular la **probabilidad a posteriori** de que haya gas ($\theta_1$) o no ($\theta_2$)) dadas las nuevas evidencias (resultado de la prueba).

El teorema de Bayes se expresa como:

$P(\theta_1 | \text{Prueba indica no gas}) = \frac{P(\text{Prueba indica no gas} | \theta_1) P(\theta_1)}{P(\text{Prueba indica no gas})}$

Donde:

$P(\text{Prueba indica no gas}) = P(\text{Prueba indica no gas} | \theta_1) P(\theta_1) + P(\text{Prueba indica no gas} | \theta_2) P(\theta_2)$


### Paso 1: Cálculo de \( P(\text{Prueba indica no gas}) \)

$P(\text{Prueba indica no gas}) = (0.3 \times 0.6) + (0.9 \times 0.4)$
$P(\text{Prueba indica no gas}) = 0.18 + 0.36 = 0.54$


### Paso 2: Cálculo de la probabilidad a posteriori
$P(\theta_1 | \text{Prueba indica no gas}) = \frac{0.3 \times 0.6}{0.54} = \frac{0.18}{0.54} = 0.333$


### Paso 3: Cálculo de la probabilidad a posteriori $P(\theta_2 | \text{Prueba indica no gas})$
$P(\theta_2 | \text{Prueba indica no gas}) = 1 - P(\theta_1 | \text{Prueba indica no gas}) = 1 - 0.333 = 0.667$

## Análisis de decisiones a posteriori

Con las probabilidades a posteriori, se actualizan las estimaciones de los posibles resultados en la matriz de pagos. Recordemos la matriz de pagos original:

| **Decisiones/Estados de la Naturaleza** | **$\theta_1$ (Hay gas)**    | **$\theta_2$ (No hay gas)**  |
|-----------------------------------------|-----------------------------|------------------------------|
| **Acción $a_1$ (Aceptar oferta)**       | $120,000                    | $60,000                      |
| **Acción $a_2$ (Desarrollar el campo)** | $1,900,000                  | -$100,000                    |

Utilizaremos la **regla de Bayes (Valor Esperado Medio - VEM)** con las nuevas probabilidades para tomar la decisión adecuada.

### Cálculo del Valor Esperado Medio (VEM):

- **Acción $a_1$ (Aceptar oferta)**:
  $VEM}(a_1) = P(\theta_1 | \text{Prueba indica no gas}) \times 120,000 + P(\theta_2 | \text{Prueba indica no gas}) \times 60,000$
  $\text{VEM}(a_1) = (0.333 \times 120,000) + (0.667 \times 60,000) = 40,000 + 40,020 = 80,020$

- **Acción $a_2$ (Desarrollar el campo)**:
  $\text{VEM}(a_2) = P(\theta_1 | \text{Prueba indica no gas}) \times 1,900,000 + P(\theta_2 | \text{Prueba indica no gas}) \times (-100,000)$

  $\text{VEM}(a_2) = (0.333 \times 1,900,000) + (0.667 \times -100,000) = 633,700 - 66,700 = 567,000$

### Decisión recomendada

Según el **criterio a posteriori** basado en el valor esperado medio (VEM), el propietario debería **desarrollar el campo** (acción $a_2$), ya que su valor esperado posterior ($567,000) es mayor que el de aceptar la oferta ($80,020).

### Conclusión

Después de actualizar las probabilidades utilizando la nueva información proporcionada por la prueba de sonido, la decisión óptima para el propietario es **desarrollar el campo**, incluso si el resultado de la prueba sugiere que no hay gas. Esto se debe a que, a pesar del costo de la prueba, el valor esperado de desarrollar el campo sigue siendo considerablemente más alto.
