---
title: "99 - Glosario Rápido (Cheatsheet de Nomenclatura)"
tags:
  - glosario
  - cheatsheet
  - referencia
  - nomenclatura
  - glosario/conjuntos
  - glosario/logica
  - glosario/aritmetica
  - glosario/propiedades
  - glosario/fracciones
  - glosario/algebra
  - glosario/ecuaciones
  - glosario/despeje
  - glosario/proporcionalidad
  - glosario/sistemas
  - glosario/cuadraticas
  - glosario/geometria
  - glosario/trigonometria
  - glosario/inecuaciones
  - glosario/valor-absoluto
  - glosario/intervalos
  - glosario/funciones
  - glosario/probabilidad
  - glosario/simbolos
aliases: [Glosario, Cheatsheet, Nomenclatura, Referencia Rápida]
type: reference
cssclasses:
  - wide-tables
  - compact-table
---

# 99 - Glosario Rápido: Nomenclatura y Cheatsheet

> [!HOWTO] Cómo buscar en este glosario (y en todo el vault)
> Cada sección lleva sus **tags** (chips verdes debajo del encabezado). Click en un tag, o buscarlo desde cualquier parte:
>
> | Buscar | Cómo |
> |---|---|
> | Todo lo de **fracciones** | `tag:#glosario/fracciones` |
> | Las **propiedades** (distributiva, conmutativa...) | `tag:#glosario/propiedades` |
> | Frase exacta | `"denominador"` |
> | Solo en el glosario | `path:"99 - Glosario" "fracciones"` |
> | Solo dentro de una sección | `section:("valor absoluto")` |
> | Símbolos | `tag:#glosario/simbolos` |
>
> Atajos: `Ctrl+Shift+F` búsqueda global con operadores · `Ctrl+F` dentro de esta nota · `Ctrl+P` abrir por nombre o alias ("Cheatsheet").

---

## Mapa del glosario (saltar directo)

| Sección | Ir | Nota de origen |
|---|---|---|
| 1. Conjuntos numéricos | [[99 - Glosario Rápido#1. Conjuntos Numéricos\|ver]] | [[01 - Conjuntos Numéricos y Lógica\|01 · conjuntos]] |
| 2. Lógica proposicional | [[99 - Glosario Rápido#2. Lógica Proposicional\|ver]] | [[01 - Conjuntos Numéricos y Lógica\|01 · lógica]] |
| 3. Aritmética y álgebra | [[99 - Glosario Rápido#3. Aritmética y Álgebra\|ver]] | [[02 - Propiedad Distributiva\|02 · distributiva]] |
| 4. Ecuaciones y despeje | [[99 - Glosario Rápido#4. Ecuaciones y Despeje\|ver]] | [[04 - Ecuaciones Lineales y Proporcionalidad\|04 · despeje]] |
| 5. Sistemas de ecuaciones | [[99 - Glosario Rápido#5. Sistemas de Ecuaciones\|ver]] | [[06 - Sistemas de Ecuaciones\|06 · sistemas]] |
| 6. Ecuaciones cuadráticas | [[99 - Glosario Rápido#6. Ecuaciones Cuadráticas\|ver]] | [[05 - Ecuaciones Cuadráticas y Bhaskara\|05 · Bhaskara]] |
| 7. Geometría y trigonometría | [[99 - Glosario Rápido#7. Geometría y Trigonometría\|ver]] | [[07 - Teorema de Pitágoras\|07 · Pitágoras]], [[08 - Trigonometría y Circunferencia Unitaria\|08 · ángulos]] |
| 8. Inecuaciones y valor absoluto | [[99 - Glosario Rápido#8. Inecuaciones y Valor Absoluto\|ver]] | [[09 - Inecuaciones y Valor Absoluto\|09 · inecuaciones]] |
| 9. Funciones y probabilidad | [[99 - Glosario Rápido#9. Funciones y Probabilidad\|ver]] | [[10 - Funciones y Probabilidades\|10 · funciones y proba]] |
| 10. Notación de símbolos | [[99 - Glosario Rápido#10. Notación de Símbolos\|ver]] | — |

---

## 1. Conjuntos Numéricos

#glosario/conjuntos #glosario/simbolos

| Término | Notación | Es igual a |
|---|---|---|
| Naturales | $\mathbb{N}$ | Los números del conteo: $1, 2, 3, \dots$ |
| Enteros | $\mathbb{Z}$ | Naturales, sus negativos y el $0$ (nacen de la resta: $3 - 5 = -2$) |
| Racionales | $\mathbb{Q}$ | Todo $\frac{a}{b}$ con $a, b \in \mathbb{Z}$ y $b \neq 0$ (fracciones, decimales periódicos) |
| Irracionales | $\mathbb{Q}^{c}$ | Números **no** expresables como fracción de enteros: $\sqrt{2}, \pi, e$ (surgen en geometría) |
| Reales | $\mathbb{R}$ | La unión de racionales e irracionales: la recta numérica completa |
| Pertenencia | $x \in A$ | "$x$ es un elemento de $A$" |
| Unión | $A \cup B$ | Todo lo que está en $A$, en $B$, o en ambos ("o") |
| Intersección | $A \cap B$ | Lo que está en $A$ **y** en $B$ a la vez ("y") |

## 2. Lógica Proposicional

#glosario/logica

| Término                        | Notación          | Es igual a                                                                                  |
| ------------------------------ | ----------------- | ------------------------------------------------------------------------------------------- |
| Implicación                    | $P \Rightarrow Q$ | "Si pasa $P$, pasa $Q$" ($P$: premisa, $Q$: consecuencia)                                   |
| Doble implicación              | $P \iff Q$        | $P \Rightarrow Q$ y $Q \Rightarrow P$ a la vez; solo entonces se puede afirmar el recíproco |
| Falacia de implicación inversa | —                 | Inferir "si $Q$ entonces $P$" de $P \Rightarrow Q$: **inválido** si no hay doble vía        |

## 3. Aritmética y Álgebra

#glosario/aritmetica #glosario/fracciones #glosario/propiedades #glosario/algebra

| Término                | Notación                    | Es igual a                                                                                               |
| ---------------------- | --------------------------- | -------------------------------------------------------------------------------------------------------- |
| Propiedad Distributiva | $a(b+c) = ab + ac$          | El multiplicador "rompe" el paréntesis distribuyéndose sobre cada término                                |
| Factor                 | —                           | Cada cantidad que se multiplica en un producto ([[01.1 - Estructura Algebraica: Términos, Factores y Simplificación\|nota]]) |
| Producto               | $a \cdot b$                 | Resultado de una multiplicación o expresión multiplicativa tratada como bloque                           |
| Factorización          | —                           | Proceso de convertir una suma o resta de términos en una multiplicación de factores                      |
| Término                | —                           | Cada parte de una expresión separada por $+$ o $-$ ([[01.1 - Estructura Algebraica: Términos, Factores y Simplificación\|nota]]) |
| Simplificación         | —                           | Reescribir una expresión en una forma equivalente más compacta y útil sin alterar su valor              |
| Cancelación aditiva    | $a - a = 0$                 | Anulación de términos opuestos mediante el neutro aditivo ($0$)                                          |
| Cancelación multiplicativa | $\frac{a}{a} = 1$       | Reducción de factores idénticos al neutro multiplicativo ($1$, con $a \neq 0$). Solo en factores, nunca en términos de una suma |
| Binomio                | $(a+b)$                     | Expresión con dos términos; su cuadrado se desarrolla [[03 - Cuadrado de un Binomio\|rompiendo el paréntesis]]                 |
| Fracción               | $\frac{a}{b}$               | Cociente $a \div b$; $a$ = **numerador** (arriba), $b$ = **denominador** (abajo)                         |
| Numerador              | —                           | El número de arriba de una fracción: cuántas partes se toman                                             |
| Denominador            | —                           | El número de abajo: en cuántas partes iguales se divide la unidad                                        |
| Neutro multiplicativo  | $1$                         | Multiplica sin alterar: usar como $1 = \frac{4}{4}$ sirve para sumar fracciones con distinto denominador |
| Conmutatividad         | $a \cdot b = b \cdot a$     | El orden de los factores no altera el producto (también en la suma)                                      |
| Cuadrado de un binomio | $(a+b)^2 = a^2 + 2ab + b^2$ | Identidad [[03 - Cuadrado de un Binomio\|deducible]] por distributiva o por áreas (el $2ab$ son los dos productos cruzados, no mágicos)   |
| Raíz cuadrada          | $\sqrt{c}$                  | El número no negativo cuyo cuadrado es $c$                                                               |

## 4. Ecuaciones y Despeje

#glosario/ecuaciones #glosario/despeje #glosario/proporcionalidad

| Término                       | Notación                          | Es igual a                                                                                                 |
| ----------------------------- | --------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Identidad                     | $2 + 1 = 3$                       | Igualdad que se cumple para **cualquier** valor                                                            |
| Ecuación                      | $ax + b = 0$                      | Igualdad **condicional** con incógnita; se cumple para ciertos valores                                     |
| Incógnita                     | $x$                               | Valor desconocido que la ecuación debe resolver                                                            |
| Variable                      | $y$                               | Magnitud que toma distintos valores (concreta en cada modelo)                                              |
| Despeje                       | —                                 | Operaciones **simétricas idénticas en ambos miembros** para aislar $x$ (no es "pasar números mágicamente") |
| Solución                      | $x = -\frac{b}{a}$                | El valor que satisface la condición (un punto concreto)                                                    |
| Proporcionalidad directa      | $y = c \cdot x$                   | Escalar $x$ por $c$ escala a $y$ exactamente en la misma medida, con $(0,0)$ en el origen                  |
| Constante de proporcionalidad | $c = \frac{y_1}{x_1}$             | El factor que vincula las dos magnitudes                                                                   |
| Regla de tres                 | $y_2 = \frac{x_2 \cdot y_1}{x_1}$ | Fórmula mecánica que sale de calcular $c$ y aplicarlo al nuevo valor                                       |

## 5. Sistemas de Ecuaciones

#glosario/sistemas

| Término | Es igual a |
|---|---|
| Sistema $2 \times 2$ | Dos ecuaciones con dos incógnitas $(x, y)$ que deben cumplirse **simultáneamente** |
| Compatible Determinado | Las rectas se cortan en **un único** punto: existe exactamente una solución |
| Incompatible | Rectas paralelas no coincidentes: **no hay solución** (la condición es incoherente matemática) |
| Compatible Indeterminado | Rectas coincidentes: **infinitas soluciones** |
| Método de Igualación | Despejar la misma variable en ambas ecuaciones e igualar las expresiones |
| Interpretación gráfica | Resolver el sistema = hallar el punto de intersección $(x,y)$ de ambas rectas |

## 6. Ecuaciones Cuadráticas

#glosario/cuadraticas #glosario/algebra

| Término | Notación | Es igual a |
|---|---|---|
| Cuadrática | $ax^2 + bx + c = 0$ | Ecuación de segundo grado ($a \neq 0$); $a, b, c$ son sus coeficientes |
| Fórmula de Bhaskara | $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ | Resolvente: se **demuestra** con completación de cuadrados, no se memoriza a ciegas |
| Discriminante | $b^2 - 4ac$ | La cantidad bajo la raíz: define cuántas soluciones reales hay |
| Completar el cuadrado | $\left(x + \frac{b}{2a}\right)^2$ | Reescribir la expresión usando la identidad del [[03 - Cuadrado de un Binomio\|cuadrado de binomio]] **en sentido inverso** |
| Raíz / cero | — | Valor de $x$ donde la [[10 - Funciones y Probabilidades\|parábola]] corta al eje |
| $\pm$ | doble signo | Hay dos caminos posibles: con $+$ y con $-$ |

## 7. Geometría y Trigonometría

#glosario/geometria #glosario/trigonometria

| Término | Notación | Es igual a |
|---|---|---|
| Triángulo rectángulo | — | Triángulo con un ángulo recto de $90^\circ$ ($\frac{\pi}{2}$ radianes) |
| Catetos | $a, b$ | Los dos lados que forman el ángulo recto |
| Hipotenusa | $h$ | El lado opuesto al ángulo recto, el mayor: $h = \sqrt{a^2 + b^2}$ |
| Teorema de Pitágoras | $h^2 = a^2 + b^2$ | Cuadrado de la hipotenusa = suma de los cuadrados de los catetos (demostrado por áreas) |
| Grados sexagesimales | $^\circ$ | Dividen la vuelta completa en $360^\circ$ |
| Radián | $\text{rad}$ | Ángulo medido por la longitud de arco que cubre un radio sobre el círculo; vuelta completa $= 2\pi$ rad |
| Circunferencia unitaria | $R = 1$ | Círculo de radio 1 centrado en el origen; escenario de las definiciones trigonométricas |
| Seno | $\sin(\alpha)$ | Coordenada $y$ del punto terminal $P$ en la circunferencia unitaria |
| Coseno | $\cos(\alpha)$ | Coordenada $x$ de ese punto $P$ |
| Tangente | $\tan(\alpha)$ | Cociente $\frac{\sin(\alpha)}{\cos(\alpha)} = \frac{y}{x}$ |
| Identidad fundamental | $\cos^2(\alpha) + \sin^2(\alpha) = 1$ | Pitágoras aplicado dentro del círculo unitario |
| Teorema del Seno | $\frac{a}{\sin(\alpha)} = \frac{b}{\sin(\beta)} = \frac{c}{\sin(\gamma)}$ | Relación lado/ángulo válida para **cualquier** triángulo |
| Teorema del Coseno | $c^2 = a^2 + b^2 - 2ab\cos(\gamma)$ | Generalización de Pitágoras para triángulos no rectángulos |

## 8. Inecuaciones y Valor Absoluto

#glosario/inecuaciones #glosario/valor-absoluto #glosario/intervalos

| Término | Notación | Es igual a |
|---|---|---|
| Inecuación | $<, >, \le, \ge$ | Condición de **desigualdad** sobre $x$; su solución es un intervalo, no un punto |
| Sentido de la desigualdad | — | La dirección $<$ / $>$; se conserva al sumar/restar y al operar con positivos |
| Regla crítica | — | Multiplicar o dividir por un **negativo invierte el sentido** obligatoriamente ($10 > 6 \to -20 < -12$) |
| Valor absoluto | $\|x\|$ | Distancia de $x$ al origen $0$ en la recta (siempre $\ge 0$) |
| Intervalo cerrado | $[-a, a]$ | Con extremos incluidos ($\le, \ge$); resuelve $\|x\| \le a$: entorno alrededor de 0 |
| Intervalo abierto | $(-\infty, -a] \cup [a, +\infty)$ | Exterior de la zona de ancho $2a$: resuelve $\|x\| \ge a$ |
| $\infty$ | infinito | No es un número: indica que el intervalo **no tiene tope** en esa dirección |

## 9. Funciones y Probabilidad

#glosario/funciones #glosario/probabilidad

| Término | Notación | Es igual a |
|---|---|---|
| Función | $y = f(x)$ | Regla que asigna a cada valor de $x$ **un único** valor de $y$ |
| Variable independiente | $x$ | La cantidad que varía libremente (ej. tiempo) |
| Variable dependiente | $y$ | La cuyo valor **depende** de $x$ (ej. temperatura, precio) |
| Función lineal | $f(x) = mx + b$ | Recta; generaliza a la [[04 - Ecuaciones Lineales y Proporcionalidad\|proporcionalidad]] con punto de arranque $b$ |
| Función cuadrática | $f(x) = ax^2 + bx + c$ | Parábola; sus raíces salen de [[05 - Ecuaciones Cuadráticas y Bhaskara\|completar el cuadrado]] |
| Intersección de rectas | $f_1(x) = f_2(x)$ | El punto donde las gráficas se cruzan: exactamente lo que [[06 - Sistemas de Ecuaciones\|resuelve el sistema]] |
| Espacio muestral | $\Omega$ | El conjunto de **todos** los resultados posibles de un experimento |
| Evento / suceso | $E$ | Un subconjunto de $\Omega$; lo que puede ocurrir |
| Probabilidad Laplaciana | $P(E) = \frac{\text{Casos Favorables}}{\text{Casos Totales}}$ | Sucesos equiprobables; da un valor entre $0$ (imposible) y $1$ (seguro) |
| Probabilidad condicional | $P(A \mid B)$ | Mide la probabilidad de que ocurra $A$ **sabiendo que ya ocurrió** $B$: $P(A \mid B) = \frac{P(A \cap B)}{P(B)}$ — nace de la [[01 - Conjuntos Numéricos y Lógica\|intersección]] $A \cap B$ |

## 10. Notación de Símbolos

#glosario/simbolos

| Símbolo | Es igual a |
|---|---|
| $\in$ | pertenece a |
| $\cup$ / $\cap$ | unión ("o") / intersección ("y") |
| $\Rightarrow$ / $\iff$ | implica / implica en ambos sentidos |
| $\neq$ / $\le$ / $\ge$ | distinto / menor o igual / mayor o igual |
| $\pm$ | ambos signos (dos casos simultáneos) |
| $\sqrt{\;}$ | raíz cuadrada |
| $\|x\|$ | valor absoluto (distancia a 0) |
| $\mathbb{N}, \mathbb{Z}, \mathbb{Q}, \mathbb{R}$ | naturales, enteros, racionales, reales |
| $\mathbb{Q}^{c}$ | irracionales (el complemento de $\mathbb{Q}$ en $\mathbb{R}$) |
| $\infty$ | infinito (frontera no alcanzable de un intervalo) |
| $\pi, e$ | irracionales de origen geométrico ($\pi \approx 3{,}14$) y analítico |
| $\Omega$ | espacio muestral |
| $P(E), P(A \mid B)$ | probabilidad de $E$; probabilidad condicional |

---

## Conexiones con otras Notas

- **Estructura del curso**: este glosario acompaña a [[00-indice-maestro|la red del curso]]; cada sección mapea a una nota del curso.
- **Errores**: los malentendidos de definiciones se listan en [[98 - Errores Comunes|los errores comunes]].
- **Roadmap**: los términos que faltan por agregar están en [[97 - Temas Pendientes por Agregar|el roadmap]].
- **Uso sugerido**: abrir esta nota en panel lateral y buscar con `Ctrl+F`, o usar los operadores del callout superior.
