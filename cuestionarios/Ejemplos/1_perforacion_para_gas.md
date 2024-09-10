# Problema 1. Analizar la perforación de un pozo para extraer gar natural

## Planteamiento del problema

Una gran compañía de energéticos ofrece al dueño de un terreno $60,000 por los derechos de exploración de gas natural en un sitio determinado y la opción para un desarrollo futuro. La opción, si se ejerce, vale $60,000 adicionales para el propietario, pero esto ocurrirá sólo si se descubre gas natural durante la etapa de exploración. El propietario, considerando que el interés de la compañía es una buena indicación de que existe gas, está tentado a desarrollar él mismo el campo. Para hacer esto, deberá contratar equipos locales con experiencia en exploración y desarrollo. El costo inicial es de $100,000, los que se perderán si no se encuentra gas. Sin embargo, si descubre gas, el propietario estima un beneficio neto de 2 millones de dólares.

## 1. Encuadre
1. En primer lugar, realiza el encuadre o planteamiento del problema.

Claro, empecemos a plantear el problema de la situación que has descrito en términos de la teoría de decisiones. 

### a. Decisor:
El decisor en este caso es el **propietario del terreno**. Este individuo debe tomar decisiones respecto a cómo proceder con la oferta de la compañía energética y la posibilidad de desarrollar exploración de gas natural por su cuenta.

### b. Decisiones:
El propietario tiene las siguientes decisiones posibles:

- **$D_1$:** Aceptar la oferta de $60,000 y permitir a la compañía realizar la exploración.
- **$D_2$:** No aceptar la oferta y no permitir la exploración por parte de la compañía.
- **$D_3$:** Decidir desarrollar por sí mismo la exploración y posible extracción de gas, lo que requiere una inversión inicial de $100,000.

### c. Estados de la naturaleza:
Los posibles estados de la naturaleza (resultados de la exploración) que pueden ocurrir son:

- **$S_1$:** Se encuentra gas natural.
- **$S_2$:** No se encuentra gas natural.

### d. Matriz de Pago:
Ahora, construyamos la matriz de pago para cada combinación de decisiones y estados de la naturaleza.

- **Para $D_1$ (Aceptar la oferta):**
  - Si $S_1$ (se encuentra gas natural): el propietario recibe $60,000.
  - Si $S_2$ (no se encuentra gas natural): el propietario recibe $60,000.

- **Para $D_2$ (No aceptar la oferta):**
  - En ambos estados ($S_1$, $S_2$): el propietario no recibe nada porque no hay exploración ni desarrollo.

- **Para $D_3$ (Desarrollar por sí mismo):**
  - Si $S_1$ (se encuentra gas natural): el beneficio neto será de $2,000,000 - $100,000 (costo inicial) = $1,900,000.
  - Si $S_2$ (no se encuentra gas natural): el propietario pierde $100,000.

Ahora podemos organizar esta información en forma de una matriz de pago:

| Decisiones/Estados | Se encuentra gas ($S_1$) | No se encuentra gas ($S_2$) |
|--------------------|-----------------------|---------------------------|
| **Aceptar oferta ($D_1$)**     | $60,000               | $60,000                     |
| **No aceptar oferta ($D_2$)**  | $0                    | $0                          |
| **Desarrollar ($D_3$)**        | $1,900,000            | -$100,000                  |

Con esta matriz, el propietario puede evaluar las diferentes decisiones disponibles en función de los posibles estados de la naturaleza y así tomar una decisión informada.

## 2. Ajuste del encuadre

En tu propuesta, une $D_2$ y $D_3$ en una misma: $D_2$ y haz de nuevo el encuadre.

Claro, vamos a unir las decisiones $D_2$ (No aceptar la oferta) y $D_3$ (Desarrollar por sí mismo) en una sola decisión, que llamaremos $D_2$. Esto simplificará la toma de decisiones del propietario en base a la oferta de la compañía de energéticos. 

### a. Decisor:
El **propietario del terreno** es el decisor que debe tomar la decisión sobre cómo proceder respecto a la oferta de la compañía energética y la posibilidad de explorar gas natural.

### b. Decisiones:
El propietario tiene las siguientes decisiones posibles:

- **$D_1$:** Aceptar la oferta de $60,000 y permitir a la compañía realizar la exploración.
- **$D_2$:** No aceptar la oferta y optar por no permitir la exploración, o decidir desarrollar él mismo la exploración, lo que implica un costo inicial de $100,000.

### c. Estados de la naturaleza:
Los posibles estados de la naturaleza (resultados de la exploración que pueden ocurrir) son:

- **$S_1$:** Se encuentra gas natural.
- **$S_2$:** No se encuentra gas natural.

### d. Matriz de Pago:
Ahora, construyamos la matriz de pago considerando las decisiones combinadas y sus respectivos resultados:

- **Para $D_1$ (Aceptar la oferta):**
  - Si $S_1$ (se encuentra gas natural): el propietario recibe $60,000.
  - Si $S_2$ (no se encuentra gas natural): el propietario recibe $60,000.

- **Para $D_2$ (No aceptar la oferta o desarrollar por sí mismo):**
  - Si $S_1$ (se encuentra gas natural): el beneficio neto será de $2,000,000 - $100,000 (costo inicial) = $1,900,000.
  - Si $S_2$ (no se encuentra gas natural): el propietario pierde $100,000.

La matriz de pago quedará de la siguiente manera:

| Decisiones/Estados | Se encuentra gas ($S_1$) | No se encuentra gas ($S_2$) |
|--------------------|-----------------------|---------------------------|
| **Aceptar oferta ($D_1$)**     | $60,000               | $60,000                     |
| **No aceptar oferta / Desarrollar ($D_2$)**  | $1,900,000           | -$100,000                  |

Esta nueva estructura facilitada permite al propietario analizar de manera más eficiente las posibles consecuencias financieras de cada decisión frente a los estados de la naturaleza y tomar una decisión informada.

## 3. Análisis bajo completa incertidumbre

A partir de tu propuesta, realiza el análisis de decisiones con cada uno de los siguientes criterios bajo completa incetidumbre: Maximin de Wald, Maximax, Hurwicz con alpha = 1/3 y Savage (incluye la matriz de pérdida de oportunidad).

Vamos a realizar el análisis de decisiones bajo completa incertidumbre utilizando los criterios solicitados. Los criterios que analizaremos son: Maximin de Wald, Maximax, Hurwicz y Savage. Primero, recordemos la matriz de pago que hemos generado:

| Decisiones/Estados | Se encuentra gas ($S_1$) | No se encuentra gas ($S_2$) |
|--------------------|-----------------------|---------------------------|
| **Aceptar oferta ($D_1$)**     | $60,000               | $60,000                     |
| **No aceptar oferta / Desarrollar ($D_2$)**  | $1,900,000           | -$100,000                  |

### a. Maximin de Wald

El criterio Maximin (o de Wald) consiste en seleccionar la alternativa que maximiza el mínimo resultado posible.

- Para $D_1$: el mínimo pago es $60,000.
- Para $D_2$: el mínimo pago es -$100,000.

**Maximin:**
- $D_1$:  $60,000 (mínimo)
- $D_2$: -$100,000 (mínimo)

**Decisión:** Escoger $D_1$ (Aceptar la oferta), ya que tiene el mayor mínimo resultado.

### b. Maximax

El criterio Maximax consiste en seleccionar la alternativa que maximiza el máximo resultado posible. 

- Para $D_1$: el máximo pago es $60,000.
- Para $D_2$: el máximo pago es $1,900,000.

**Maximax:**
- $D_1$: $60,000 (máximo)
- $D_2$: $1,900,000 (máximo)

**Decisión:** Escoger $D_2$ (No aceptar la oferta / Desarrollar), ya que tiene el mayor resultado máximo.

### c. Hurwicz (con alpha = 1/3)

El criterio de Hurwicz combina los conceptos de Maximin y Maximax ponderando cada uno de ellos con un factor de optimismo denominado alpha.

Para $alpha = 1/3$, se utiliza $1 - alpha = 2/3$.

Calculemos la utilidad de cada decisión:

- Para $D_1$:  
  $H(D_1) = \frac{1}{3} \times (60,000) + \frac{2}{3} \times (60,000) = 60,000 $
   

- Para $D_2$:  
  $ H(D_2) = \frac{1}{3} \times (1,900,000) + \frac{2}{3} \times (-100,000) $
  $ H(D_2) = \frac{1}{3} \times 1,900,000 - \frac{2}{3} \times 100,000 \) $
  $ H($D_2$) = 630,000 - 66,667 = 563,333.33 $

**Decisión:** Escoger $D_2$ (No aceptar la oferta / Desarrollar), ya que tiene un valor esperado superior.

### d. Savage

El criterio de Savage se basa en la minimización de la pérdida de oportunidad. Para ello, primero debemos calcular la Matriz de Pérdidas de Oportunidad.

### Matriz de Pérdidas de Oportunidad

Construimos una matriz de pérdidas con respecto a las decisiones, sustrayendo el pago de cada estado del resultado máximo de cada estado.

| Decisiones/Estados | Se encuentra gas ($S_1$) | No se encuentra gas ($S_2$) |
|--------------------|-----------------------|---------------------------|
| **Aceptar oferta ($D_1$)**     | 0                     | 160,000                   |
| **No aceptar oferta / Desarrollar ($D_2$)**  | 1,900,000           | 0                         |

### Cálculo de las pérdidas:

- Para $S_1$:
  - $D_1$ = $60,000; máximo = $1,900,000 -> Pérdida = $1,900,000 - $60,000 = $1,840,000
  - $D_2$ = $1,900,000; máximo = $1,900,000 -> Pérdida = $1,900,000 - $1,900,000 = $0

- Para $S_2$:
  - $D_1$ = $60,000; máximo = $60,000 -> Pérdida = $60,000 - $60,000 = $0
  - $D_2$ = -$100,000; máximo = $0 -> Pérdida = 0 - (-$100,000) = $100,000

Matriz de Pérdidas de Oportunidad:

| Decisiones/Estados | Se encuentra gas ($S_1$) | No se encuentra gas ($S_2$) |
|--------------------|-----------------------|---------------------------|
| **Aceptar oferta ($D_1$)**     | $1,840,000            | $0                         |
| **No aceptar oferta / Desarrollar ($D_2$)**  | $0                   | $100,000                   |

Ahora buscamos el máximo de las pérdidas para cada decisión:

- Para $D_1$: máximo de pérdidas = $1,840,000
- Para $D_2$: máximo de pérdidas = $100,000

**Decisión:** Escoger $D_2$ (No aceptar la oferta / Desarrollar), ya que tiene la menor pérdida máxima.

### Resumen de decisiones:
- **Maximin:** $D_1$ (Aceptar la oferta)
- **Maximax:** $D_2$ (No aceptar la oferta / Desarrollar)
- **Hurwicz:** $D_2$ (No aceptar la oferta / Desarrollar)
- **Savage:** $D_2$ (No aceptar la oferta / Desarrollar)

En conclusión, la mayoría de los criterios sugieren que es preferible optar por no aceptar la oferta y desarrollar por sí mismo la exploración.

## 4. Análisis bajo riesgo

Ahora, a partir de los datos del problema inicial, determina las decisiones recomendables, bajo riesgo o con métodos sin experimentación, bajo los siguientes criterios: Laplace, Máxima Posibilidad, Bayes (VEM) y Minimización de la oportunidad de pérdida esperada (POE). Crea la matriz extendida y agrega las probabilidades para cada estado de la naturaleza en una fila. Para cada criterio, exhibe la matriz de pago con esos datos adicionales.

Para realizar el análisis de decisiones bajo riesgo utilizando los métodos solicitados (Laplace, Máxima Posibilidad, Bayes), vamos a incorporar probabilidades a los estados de la naturaleza ($S_1$ y $S_2$). Asumiremos las siguientes probabilidades para los resultados:

- **P($S_1$) = 0.3** (probabilidad de que se encuentre gas natural).
- **P($S_2$) = 0.7** (probabilidad de que no se encuentre gas natural).

Ahora, vamos a crear la matriz extendida que incluya las probabilidades de los estados de la naturaleza en una fila. 

### Matriz de Pago Extendida

| Decisiones/Estados | Se encuentra gas ($S_1$) | No se encuentra gas ($S_2$) | Probabilidades |
|--------------------|-----------------------|---------------------------|-----------------|
| **Aceptar oferta ($D_1$)**     | $60,000               | $60,000                     | 0.3             |
| **No aceptar oferta / Desarrollar ($D_2$)**  | $1,900,000           | -$100,000                  | 0.7             |

### a. Criterio de Laplace

El criterio de Laplace asigna la misma probabilidad a cada estado de la naturaleza, independientemente de las probabilidades reales.

- Hay 2 estados, entonces la probabilidad de cada uno es: \(P($S_1$) = P($S_2$) = 0.5\).

**Cálculo Laplace:**
- Para $D_1$: 
  $$$
  U(D_1) = \frac{1}{2} \times 60,000 + \frac{1}{2} \times 60,000 = 60,000
  $$$
- Para $D_2$:
  $$$
  U(D_2) = \frac{1}{2} \times 1,900,000 + \frac{1}{2} \times (-100,000) = \frac{1,900,000 - 100,000}{2} = \frac{1,800,000}{2} = 900,000
  $$$

**Decisión:** Escoger $D_2$.

### b. Criterio de Máxima Posibilidad

Este criterio selecciona la alternativa asociada al estado de la naturaleza más probable ($S_2$, en este caso).

**Decisión:** Escoger $D_2$, ya que la probabilidad de $S_2$ es mayor (0.7).

### c. Criterio de Bayes (Valor Esperado de la Máxima)

Se calcula el valor esperado (VE) de cada decisión, teniendo en cuenta las probabilidades dadas.

**Cálculo del Valor Esperado:**
- Para $D_1$:
  $$$
  VE(D_1) = P(S_1) \times 60,000 + P(S_2) \times 60,000
  $$$
  $$$
  VE(D_1) = 0.3 \times 60,000 + 0.7 \times 60,000 = 60,000
  $$$

- Para $D_2$:
  $$$
  VE(D_2) = P(S_1) \times 1,900,000 + P(S_2) \times (-100,000)
  $$$
  $$$
  VE(D_2) = 0.3 \times 1,900,000 + 0.7 \times (-100,000) = 570,000 - 70,000 = 500,000
  $$$

**Decisión:** Escoger $D_1$, ya que su valor esperado es superior.

### d. Minimización de la Oportunidad de Pérdida Esperada (POE)

Para el criterio de minimización de la oportunidad de pérdida esperada, primero necesitamos calcular la matriz de pérdidas.

#### Matriz de Pérdidas (POE)

Calculamos la pérdida para cada decisión, sustrayendo el pago de cada estado del resultado máximo de cada estado.

- Para $S_1$: 
  - $D_1$ = $60,000; máximo = $1,900,000 → Pérdida = $1,900,000 - $60,000 = $1,840,000 
  - $D_2$ = $1,900,000; máximo = $1,900,000 → Pérdida = $1,900,000 - $1,900,000 = $0

- Para $S_2$:
  - $D_1$ = $60,000; máximo = $60,000 → Pérdida = $60,000 - $60,000 = $0 
  - $D_2$ = -$100,000; máximo = $0 → Pérdida = 0 - (-$100,000) = $100,000 

Matriz de Pérdidas:

| Decisiones/Estados | Se encuentra gas ($S_1$) | No se encuentra gas ($S_2$) |
|--------------------|-----------------------|---------------------------|
| **Aceptar oferta ($D_1$)**     | $1,840,000            | $0                         |
| **No aceptar oferta / Desarrollar ($D_2$)**  | $0                   | $100,000                   |

Calculamos ahora el valor esperado de pérdidas para cada decisión:
- Para $D_1$:
  $$$
  VE_{\text{Pérdidas}}(D_1) = 0.3 \times 1,840,000 + 0.7 \times 0 = 552,000
  $$$
- Para $D_2$:
  $$$
  VE_{\text{Pérdidas}}(D_2) = 0.3 \times 0 + 0.7 \times 100,000 = 70,000 
  $$$

**Decisión:** Escoger $D_2$, ya que tiene una menor pérdida esperada.

### Resumen de decisiones:
- **Laplace:** $D_2$
- **Máxima Posibilidad:** $D_2$
- **Bayes (Valor Esperado):** $D_1$
- **Minimización de POE:** $D_2$

Esto nos da una idea de cómo se debe actuar bajo diferentes criterios de decisión bajo riesgo. Algunos criterios están alineados en preferir $D_2$, mientras que el criterio de Bayes sugiere optar por $D_1$.

## 5. Análisis bajo experimentación 

A partir de los datos del problema inicial, considera el siguiente escenario: El propietario ha decidido realizar pruebas con sonido en el sitio en donde se sospecha que haya gas natural, con un costo de $30,000. Las pruebas de sonido indican que no hay gas presente, pero la prueba no es perfecta. La compañía que realizó las pruebas acepta que 30% de las veces la prueba indicará que no hay gas cuando en realidad éste existe. Cuando no existe gas, la prueba es acertada 90% de las veces. Empleando estos datos, actualícese la estimación inicial del propietario de que la probabilidad de encontrar gas es de 0.6 y determínese después la decisión recomendada bajo el criterio a posteriori. Exhibe la nueva matriz de pagos que se utilizará para el análisis y desarrolla el árbol de decisiones correspondiente.

Para analizar este nuevo escenario de decisión, utilizaremos el Teorema de Bayes para actualizar nuestras probabilidades iniciales basadas en la nueva información proporcionada por las pruebas de sonido. Además, elaboraremos una nueva matriz de pagos y un árbol de decisiones.

### Paso 1: Definición de las Probabilidades Iniciales

- **Probabilidad inicial de encontrar gas ($ P(G) $) = 0.6**
- **Probabilidad de no encontrar gas ($ P(\neg G) $) = 0.4**

### Paso 2: Resultados de las Pruebas de Sonido

- Probabilidad de que la prueba indique que **no hay gas** ($ T_{\neg G} $) cuando efectivamente hay gas ($ P(T_{\neg G} | G) $) = 0.3
- Probabilidad de que la prueba indique que **no hay gas** (\( T_{\neg G} \)) cuando efectivamente no hay gas ($ P(T_{\neg G} | \neg G) $) = 0.1 (es decir, 90% de acierto significa 10% de error).
  
### Paso 3: Cálculo de Probabilidades A Posteriori

Usando el Teorema de Bayes, actualizamos la probabilidad a posteriori de que hay gas dado que la prueba indica que no hay gas:

$$$
P(G | T_{\neg G}) = \frac{P(T_{\neg G} | G) \cdot P(G)}{P(T_{\neg G})}
$$$

Primero, tenemos que calcular \( P(T_{\neg G}) \):
$$$
P(T_{\neg G}) = P(T_{\neg G} | G) \cdot P(G) + P(T_{\neg G} | \neg G) \cdot P(\neg G)
$$$
$$$
P(T_{\neg G}) = (0.3 \cdot 0.6) + (0.1 \cdot 0.4) = 0.18 + 0.04 = 0.22
$$$

Ahora, podemos calcular \( P(G | T_{\neg G}) \):
$$$
P(G | T_{\neg G}) = \frac{0.3 \cdot 0.6}{0.22} = \frac{0.18}{0.22} \approx 0.8182
$$$

Y, por consiguiente:
$$$
P(\neg G | T_{\neg G}) = 1 - P(G | T_{\neg G}) = 1 - 0.8182 \approx 0.1818
$$$

### Paso 4: Creación de la Nueva Matriz de Pagos

Con las probabilidades a posteriori, procedemos a construir la nueva matriz de pagos:

### Nueva Matriz de Pagos

| Decisiones/Estados                     | Se encuentra gas (G) | No se encuentra gas (\( \neg G \)) | Probabilidades A Posteriori |
|----------------------------------------|-----------------------|-------------------------------------|-----------------------------|
| **Aceptar oferta ($D_1$)**               | $60,000               | $60,000                             | 0.8182                      |
| **No aceptar oferta / Desarrollar ($D_2$)** | $1,900,000           | -$100,000                          | 0.1818                      |

### Paso 5: Cálculo de los Valores Esperados

Ahora, calculamos el Valor Esperado para cada opción:

- Para $D_1$:
  $$$
  VE(D_1) = P(G | T_{\neg G}) \cdot 60,000 + P(\neg G | T_{\neg G}) \cdot 60,000
  $$$
  $$$
  VE(D_1) = 0.8182 \cdot 60,000 + 0.1818 \cdot 60,000 = 60,000
  $$$

- Para $D_2$:
  $$$
  VE(D_2) = P(G | T_{\neg G}) \cdot 1,900,000 + P(\neg G | T_{\neg G}) \cdot (-100,000)
  $$$
  $$$
  VE(D_2) = 0.8182 \cdot 1,900,000 + 0.1818 \cdot (-100,000)
  $$$
  $$$
  VE($D_2$) = 1,555,556 - 18,182 \approx 1,537,374
  $$$

### Paso 6: Decisión Recomendada Bajo el Criterio a Posteriori

**Decisión:** Escoger $D_2$ (No aceptar la oferta / Desarrollar), ya que su Valor Esperado es significativamente mayor que D1.

### Paso 7: Árbol de Decisiones

A continuación se presenta el árbol de decisiones:

```
                  [Decisión: Prueba de Sonido]
                           /          \
                          /            \
            [No Hay Gas]             [Hay Gas]
             (0.1818)                    (0.8182)
             /    \                      /        \
           D1      $D_2$                 D1          $D_2$
        (60,000)  (1,900,000)     (60,000)   (1,900,000)
```

### Resumen

La decisión recomendada después de realizar las pruebas de sonido y aplicar el Teorema de Bayes es no aceptar la oferta y proceder con el desarrollo, dado que se maximiza el valor esperado a partir de la información actualizada.

## 6. Otro escenario: Las indican que hay gas. 

Ahora, resuélvase el problema considerando que las pruebas de sonido indicaron que había gas presente. Hágase un árbol de decisión.

Si las pruebas de sonido indican que hay gas presente, necesitamos reevaluar las probabilidades y los pagos asociados antes de tomar una decisión. Usaremos el Teorema de Bayes para actualizar nuestras probabilidades a posteriori con esta nueva información y luego construiremos un árbol de decisiones correspondiente.

### Paso 1: Definición de las Probabilidades Iniciales

- **Probabilidad inicial de encontrar gas (\( P(G) \)) = 0.6**
- **Probabilidad de no encontrar gas (\( P(\neg G) \)) = 0.4**

### Paso 2: Resultados de las Pruebas de Sonido

En este caso, tenemos que calcular:

- Probabilidad de que la prueba indique que **hay gas** (\( T_G \)) cuando en realidad hay gas (\( P(T_G | G) \)) = 0.7 (es decir, 1 - 0.3).
- Probabilidad de que la prueba indique que **hay gas** (\( T_G \)) cuando en realidad no hay gas (\( P(T_G | \neg G) \)) = 0.1 (es decir, 1 - 0.9).

### Paso 3: Cálculo de Probabilidades A Posteriori

Usando el Teorema de Bayes:

$$$
P(G | T_G) = \frac{P(T_G | G) \cdot P(G)}{P(T_G)}
$$$

Calcularemos primero \( P(T_G) \):
$$$
P(T_G) = P(T_G | G) \cdot P(G) + P(T_G | \neg G) \cdot P(\neg G)
$$$
$$$
P(T_G) = (0.7 \cdot 0.6) + (0.1 \cdot 0.4) = 0.42 + 0.04 = 0.46
$$$

Ahora, podemos calcular \( P(G | T_G) \):
$$$
P(G | T_G) = \frac{0.7 \cdot 0.6}{0.46} = \frac{0.42}{0.46} \approx 0.9130
$$$

Y, por lo tanto:
$$$
P(\neg G | T_G) = 1 - P(G | T_G) = 1 - 0.9130 \approx 0.0870
$$$

### Paso 4: Construcción de la Nueva Matriz de Pagos

Usando las probabilidades a posteriori, creamos la nueva matriz de pagos:

### Nueva Matriz de Pagos

| Decisiones/Estados                     | Se encuentra gas (G) | No se encuentra gas (\( \neg G \)) | Probabilidades A Posteriori |
|----------------------------------------|-----------------------|-------------------------------------|-----------------------------|
| **Aceptar oferta ($D_1$)**               | $60,000               | $60,000                             | 0.9130                      |
| **No aceptar oferta / Desarrollar ($D_2$)** | $1,900,000           | -$100,000                          | 0.0870                      |

### Paso 5: Cálculo de los Valores Esperados

Ahora, calculamos el Valor Esperado (VE) para cada opción:

- Para $D_1$:
  $$$
  VE(D_1) = P(G | T_G) \cdot 60,000 + P(\neg G | T_G) \cdot 60,000
  $$$
  $$$
  VE(D_1) = 0.9130 \cdot 60,000 + 0.0870 \cdot 60,000
  $$$
  $$$
  VE(D_1) = 54,780 + 5,220 = 60,000
  $$$

- Para $D_2$:
  $$$
  VE($D_2$) = P(G | T_G) \cdot 1,900,000 + P(\neg G | T_G) \cdot (-100,000)
  $$$
  $$$
  VE($D_2$) = 0.9130 \cdot 1,900,000 + 0.0870 \cdot (-100,000)
  $$$
  $$$
  VE($D_2$) = 1,734,700 - 8,700 = 1,726,000
  $$$

### Paso 6: Decisión Recomendada Bajo el Criterio A Posteriori

**Decisión:** Escoger $D_2$ (No aceptar la oferta / Desarrollar), ya que su Valor Esperado es mayor que $D_1$ (1,726,000 vs 60,000).

### Paso 7: Árbol de Decisiones

A continuación, se presenta el árbol de decisiones con el resultado de las pruebas de sonido que indican que hay gas presente.

```
                             [Decisión: Prueba de Sonido]
                                   /          \
                                  /            \
                        [Hay Gas (0.9130)]    [No Hay Gas (0.0870)]
                                   /                    \
                                 D1                      $D_2$
                          (Pago $60,000)          (Pago $1,900,000)
                                                  (Pago -$100,000)
```

### Resumen

Con base en el resultado de que las pruebas de sonido indican que hay gas presente, se recomienda no aceptar la oferta y proceder con el desarrollo, dado que se maximiza el valor esperado a partir de la información actualizada.

## 7. Otro escenario: Las pruebas no se ha realizado

Por último, analiza cuál es la decisión recomendada si las pruebas de sonido tratadas anteriormente no se han realizado, sino solamente se están considerando. Usa un árbol de decisión.

Cuando las pruebas de sonido aún no se han realizado y se está considerando si hacerlas o no, comenzaremos con las probabilidades iniciales del problema y decidiremos basándonos en el valor esperado de las opciones disponibles, incluyendo la realización de las pruebas de sonido.

### Paso 1: Definición de las Probabilidades Iniciales

- **Probabilidad inicial de encontrar gas (\( P(G) \)) = 0.6**
- **Probabilidad de no encontrar gas (\( P(\neg G) \)) = 0.4**

### Paso 2: Opciones Disponibles

Las decisiones disponibles en este caso son:

1. Realizar pruebas de sonido ($D_1$).
2. No realizar pruebas y decidir directamente sobre la oferta ($D_2$).

### Paso 3: Cálculo de Valores Esperados Sin Realizar Pruebas

#### Si No Se Realizan Pruebas de Sonido

Si no se realizan las pruebas de sonido, el valor esperado se basa en la decisión de aceptar la oferta o no.

- **Aceptar la oferta ($D_2$)**:
  - Valor: $60,000 (si hay gas) o $60,000 (si no hay gas).
  - Valor Esperado (VE):
  $$$
  VE($D_2$) = P(G) \cdot 60,000 + P(\neg G) \cdot 60,000 = 0.6 \cdot 60,000 + 0.4 \cdot 60,000 = 60,000
  $$$

- **No aceptar la oferta ($D_3$)**:
  - Valor: $1,900,000 (si hay gas) o -$100,000 (si no hay gas).
  - Valor Esperado (VE):
  $$$
  VE($D_3$) = P(G) \cdot 1,900,000 + P(\neg G) \cdot (-100,000)
  $$$
  \[
  VE($D_3$) = 0.6 \cdot 1,900,000 + 0.4 \cdot (-100,000)
  $$$
  $$$
  VE($D_3$) = 1,140,000 - 40,000 = 1,100,000
  $$$

### Paso 4: Cálculo de Valores Esperados Si Se Realizan Pruebas de Sonido

Ahora consideramos la opción de realizar pruebas de sonido ($D_1$):

#### Valores Esperados Si Se Realizan Pruebas

1. **Si hacemos pruebas ($D_1$)**, entonces tenemos los siguientes resultados posibles:

   - **Hay gas (70% probabilidad)**
     - Aceptamos la oferta ($D_2$): $60,000
     - No aceptamos la oferta ($D_3$): $1,900,000
   - **No hay gas (10% probabilidad)**
     - Aceptamos la oferta ($D_2$): $60,000
     - No aceptamos la oferta ($D_3$): -$100,000
     
Las probabilidades de los resultados después de hacer las pruebas serían:

$$$
P(T_G | G) = 0.7 \quad \text{y} \quad P(T_G | \neg G) = 0.1
$$$

Calculamos primero \( P(T_G) \):

$$$
P(T_G) = P(T_G | G) \cdot P(G) + P(T_G | \neg G) \cdot P(\neg G) 
$$$

$$$
P(T_G) = (0.7 \cdot 0.6) + (0.1 \cdot 0.4) = 0.42 + 0.04 = 0.46
$$$

Ahora para las probabilidades a posteriori:

$$$
P(G | T_G) = \frac{P(T_G | G) \cdot P(G)}{P(T_G)} = \frac{0.7 \cdot 0.6}{0.46} \approx 0.913
$$$

$$$
P(\neg G | T_G) = 1 - P(G | T_G) \approx 0.087
$$$

#### Valores Esperados Después de Pruebas

- **Aceptar oferta tras pruebas ($D_2$)**:
$$$
VE($D_2$) = P(G | T_G) \cdot 60,000 + P(\neg G | T_G) \cdot 60,000
$$$
$$$
VE($D_2$) = 0.913 \cdot 60,000 + 0.087 \cdot 60,000 = 60,000
$$$

- **No aceptar oferta tras pruebas ($D_3$)**:
$$$
VE($D_3$) = P(G | T_G) \cdot 1,900,000 + P(\neg G | T_G) \cdot (-100,000)
$$$
$$$
VE($D_3$) = 0.913 \cdot 1,900,000 + 0.087 \cdot (-100,000)
$$$
$$$
VE($D_3$) = 1,734,700 - 8,700 = 1,726,000
$$$

### Paso 5: Decisión Recomendada

Ahora que hemos calculado los valores esperados, podemos organizarlo en el árbol de decisión.

### Estructura del Árbol de Decisión

```
                      [Decisión: Realizar Pruebas de Sonido]
                              /                     \
                   [Realizar Pruebas]             [No Realizar Pruebas]
                   /              \                           /               \
              [Con Gas]        [Sin Gas]               [Aceptar Oferta]   [No Aceptar Oferta]
               (0.913)          (0.087)                        |                  |
                /     \          /     \                  (60,000)           (1,100,000)
         $D_2$      $D_3$      $D_2$     $D_3$
      (60,000) (1,726,000)   (60,000)  (-100,000)
```

### Resultados Finales

- **Sin realizar pruebas**, el valor esperado de no aceptar la oferta y desarrollar es **1,100,000**.
- **Realizando pruebas**, el valor esperado de no aceptar es **1,726,000**.

### Decisión Recomendada

Dado que la opción de no realizar pruebas y proceder a desarrollar tiene un valor esperado de **1,100,000**, y la opción de realizar pruebas y luego desarrollar tiene un valor esperado de **1,726,000**, la **decisión recomendada es realizar las pruebas de sonido** antes de tomar una decisión sobre aceptar la oferta.

Esto maximiza el valor esperado de la decisión bajo la incertidumbre de no saber si hay gas presente.

