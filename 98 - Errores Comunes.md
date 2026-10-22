---
title: "98 - Errores Comunes"
tags: [errores, armaduras, disciplina, referencia]
aliases: [Errores Comunes, Armaduras]
type: warning
cssclasses:
  - wide-tables
  - compact-table
---

# 98 - Errores Comunes: las Trampas del Curso

> [!WARNING] Filosofía
> Casi todo error de cálculo nace de un **concepto mal construido**, no de un descuido. Por eso cada remedio está tejido en el texto: el enlace viaja sobre la palabra que nombra la idea que arregla el problema. Consulta esta lista **antes** de decir "me dio mal y no sé por qué".

---

## 1. Álgebra Básica

| Error común ✗ | Lo correcto ✓ | Por qué pasa |
|---|---|---|
| $(a+b)^2 = a^2 + b^2$ | $(a+b)^2 = a^2 + 2ab + b^2$ | Olvidar los [[03 - Cuadrado de un Binomio\|dos productos cruzados]] $ab + ba = 2ab$ que produce el desarrollo |
| $\sqrt{a+b} = \sqrt{a} + \sqrt{b}$ | No existe tal descomposición | Tratar la raíz como si fuera [[02 - Propiedad Distributiva\|distributiva]], que **solo** rompe paréntesis de multiplicación |
| Sumar fracciones como $\frac{a}{c} + \frac{b}{d} = \frac{a+b}{c+d}$ | $\frac{a d + b c}{c d}$ | Confundir "denominador común" con "sumar denominadores": se compone todo con el [[99 - Glosario Rápido#3. Aritmética y Álgebra\|neutro multiplicativo]] $\frac{4}{4}, \frac{3}{3}$ |
| Cancelar "términos" en una suma: $\frac{a + b}{a} \neq \frac{b}{a}$ (correcto: $1 + \frac{b}{a}$) | Cancelación solo en **productos** ($\frac{ab}{ac} = \frac{b}{c}$, con $a \neq 0$) | Cancelar es dividir arriba y abajo por el [[04 - Ecuaciones Lineales y Proporcionalidad\|mismo factor]], y en la suma no hay factor común al total |

---

## 2. Potencias y Signos

| Error común ✗ | Lo correcto ✓ | Por qué pasa |
|---|---|---|
| $-2^2 = (-2)^2 = 4$ | $-2^2 = -4$; en cambio $(-2)^2 = 4$ | El cuadrado compacta solo lo [[03 - Cuadrado de un Binomio\|encerrado en el paréntesis]]; el signo exterior no eleva |
| Elevar paréntesis al cuadrado y olvidar la lectura: $\sqrt{x^2} = x$ y de ahí $\sqrt{(x+3)^2} = x + 3$ | $\sqrt{x^2} = \|x\|$ | La raíz devuelve lo **no negativo**: ese [[05 - Ecuaciones Cuadráticas y Bhaskara\|valor absoluto]] es el que más tarde produce los dos casos del $\pm$ |
| Dividir por $x$ en $x^2 = x \cdot 5$ y quedarse con $x = 5$ | Factorizar: $x(x - 5) = 0 \Rightarrow x = 0$ **o** $x = 5$ | Al dividir por un valor que puede ser $0$, **se pierde la solución** $x = 0$: factorizar antes que [[04 - Ecuaciones Lineales y Proporcionalidad\|dividir por la incógnita]] |

---

## 3. Ecuaciones y Despeje

| Error común ✗ | Lo correcto ✓ | Por qué pasa |
|---|---|---|
| "El $+3$ pasa al otro lado como $-3$" | Restar $3$ **a ambos miembros**: $x + 3 - 3 = 7 - 3$ | El [[04 - Ecuaciones Lineales y Proporcionalidad\|despeje]] es una operación **simétrica en ambos lados**, no un traslado mágico |
| Tratar la identidad como ecuación: $2(x+1) = 2x + 2 \Rightarrow x = x$ ("contradicción") | Si queda $x = x$ o $2 = 2$: son **infinitas** soluciones (identidad); $3 = 1$: **ninguna** solución | Cuando la variable desaparece, la igualdad habla de verdad o de contradicción — y eso es exactamente lo que usa [[06 - Sistemas de Ecuaciones\|la clasificación de sistemas]] |
| Sistema incompatible: seguir buscando valores de $x$ cuando aparece $3 = 1$ | Concluir sin solución: quedaría frente a rectas [[06 - Sistemas de Ecuaciones\|paralelas no coincidentes]] | La incoherencia del sistema no es una pista para despejar más: es la respuesta |
| Aplicar Bhaskara sin el $\pm$: $x = \frac{-b + \sqrt{b^2 - 4ac}}{2a}$ como única raíz | El doble signo $\pm$ produce **dos** raíces: $x_1$ y $x_2$ | La raíz de un cuadrado se lee con [[05 - Ecuaciones Cuadráticas y Bhaskara\|valor absoluto]] y admite dos lecturas: el $\pm$ no es decorativo |
| Discriminante: $\sqrt{b^2} - 4ac$ (raíz solo de $b^2$) | $\sqrt{b^2 - 4ac}$ (la raíz cubre **todo** el radical) | El radical alcanza completo al [[05 - Ecuaciones Cuadráticas y Bhaskara\|discriminante]]: la raíz no se recorta al primer término |

---

## 4. Desigualdades

| Error común ✗ | Lo correcto ✓ | Por qué pasa |
|---|---|---|
| Multiplicar por negativo sin invertir: $-2x > 6 \Rightarrow x > -3$ | $x < -3$ (**invierte el sentido**) | En la recta numérica el orden se da vuelta: $10 > 6$ pasa a $-12 < -20$ tras multiplicar por $-2$, y la [[09 - Inecuaciones y Valor Absoluto\|desigualdad]] debe acompañarlo |
| $\|x\| \ge a \Rightarrow -a \le x \le a$ | $\|x\| \le a \Rightarrow -a \le x \le a$ (entorno); $\|x\| \ge a \Rightarrow$ **zonas exteriores** en unión | El valor absoluto mide [[09 - Inecuaciones y Valor Absoluto\|distancia al origen]]: distancia chica es estar cerca (el centro); distancia grande es estar lejos (**los dos extremos**), no adentro |
| Tratar $\infty$ como número: $-\infty < x < \infty$ "mayor que infinito" | $\infty$ solo marca que el intervalo **no tiene tope** | Una [[09 - Inecuaciones y Valor Absoluto\|frontera abierta]] indica dirección, no valor: no hay nada que comparar contra ella |

---

## 5. Geometría y Trigonometría

| Error común ✗ | Lo correcto ✓ | Por qué pasa |
|---|---|---|
| Aplicar Pitágoras a cualquier triángulo: $c^2 = a^2 + b^2$ siempre | Solo al **triángulo rectángulo**; en general: $c^2 = a^2 + b^2 - 2ab\cos(\gamma)$ | Pitágoras es el caso particular $\gamma = 90^\circ$ del [[07 - Teorema de Pitágoras\|teorema del coseno]]: sin el ángulo recto, falta el término coseno |
| Mezclar grados y radianes: $\sin(30$ rad$)$ pensando en $30^\circ$ | Convertir: $30^\circ = \frac{30 \cdot \pi}{180} = \frac{\pi}{6}$ rad | Grados y [[08 - Trigonometría y Circunferencia Unitaria\|radianes]] son dos escalas del mismo ángulo ($360^\circ = 2\pi$ rad): conviene antes de usarla |
| $\sin^2\alpha + \cos^2\alpha = 1 \Rightarrow \sin\alpha + \cos\alpha = 1$ | Nada de $\sin + \cos = 1$: solo vale el cuadrado | [[02 - Propiedad Distributiva\|El cuadrado no distribuye]] sobre la suma: el mismo error estructural $(a+b)^2 = a^2+b^2$, con otra ropa |
| Usar el valor exacto $\pi = 3{,}14$ o $2\pi = 6{,}28$ | $\pi \approx 3{,}14$; $2\pi \approx 6{,}28\ R$ (**aprox**, es irracional) | El [[01 - Conjuntos Numéricos y Lógica\|número irracional]] $\pi$ no tiene decimal exacto: el símbolo honesto con un redondeo es $\approx$ |

---

## 6. Lógica, Conjuntos y Probabilidad

| Error común ✗ | Lo correcto ✓ | Por qué pasa |
|---|---|---|
| De $P \Rightarrow Q$ inferir $Q \Rightarrow P$ | Solo con doble implicación $P \iff Q$; si no, afirmar el recíproco es **inválido** | La [[01 - Conjuntos Numéricos y Lógica\|implicación]] no funciona en ambos sentidos por defecto: "si es cuadrado, es rectángulo" no devuelve "si es rectángulo, es cuadrado" |
| Confundir $\cup$ (unión) con $\cap$ en la notación | $\cup$: "o"; $\cap$: "y" (los dos eventos a la vez) | Se distinguen con el [[10 - Funciones y Probabilidades\|diagrama de Venn]]: la superposición pinta lo intersección, la mancha completa la unión |
| $P(A \cup B) = P(A) + P(B)$ siempre | $P(A \cup B) = P(A) + P(B) - P(A \cap B)$ | La suma simple **doble-cuenta** la [[10 - Funciones y Probabilidades\|intersección]]: los casos que cumplen ambas condiciones se cobran dos veces |
| $P(A \mid B)$ igual a $P(A \cap B)$ | $P(A \mid B) = \frac{P(A \cap B)}{P(B)}$ | La condicional vive dentro del mundo donde $B$ ya ocurrió: por eso [[10 - Funciones y Probabilidades\|divide]] por esa base |
| Elegir "un evento favorable" con un conjunto **no equiprobable** | La fórmula $P(E) = \frac{\text{fav}}{\text{tot}}$ **solo vale** para casos equiprobables | Contar resultados no es lo mismo que contar [[10 - Funciones y Probabilidades\|probabilidades iguales]]: el dado cargado no es Laplace |

---

## 7. Funciones y Notación

| Error común ✗ | Lo correcto ✓ | Por qué pasa |
|---|---|---|
| Leer $f(x)$ como "$f$ por $x$" (multiplicación) | $f(x)$ es la salida de la **regla** $f$ al recibir $x$; no hay $f$-número | La [[10 - Funciones y Probabilidades\|notación $f(x)$]] se lee "la salida de $f$ en la entrada $x$": paréntesis de aplicación, no de producto |
| Cambiar $x$ por el $y$: pensar que $f(2)$ significa "la función 2" | $f(2)$ = valor de la función **cuando la entrada es** $2$ | Cada letra cumple un rol distinto: $f$ nombra la regla, el número dentro del [[10 - Funciones y Probabilidades\|paréntesis]] es la entrada |
| Confundir la forma general de una recta: $y = c\cdot x$ con la de cualquier recta $y = mx + b$ | $y = c \cdot x$ es el caso particular (pasa por el origen) de $y = mx + b$ | Una [[04 - Ecuaciones Lineales y Proporcionalidad\|proporcionalidad]] con $b \neq 0$ se rompe: escala el punto de partida y deja de ser proporcional |

---

## 8. Trampas de Interpretación (arriba de todo)

| Error común ✗ | Lo correcto ✓ | Por qué pasa |
|---|---|---|
| Memorizar Bhaskara sin saber por qué | Bhaskara se **deriva** paso a paso desde el cuadrado de un binomio | La memoria sin concepto se derrumba bajo estrés: la deducción vive en el [[03 - Cuadrado de un Binomio\|cuadrado de binomio]] |
| Saltarse la pregunta "¿qué es?" | Definir primero: evento favorable, igualmente probables, etc. | Mal definir es el error raíz de toda la cadena posterior: empezá por el [[99 - Glosario Rápido\|glosario en una línea]] |
| No revisar qué se escribió | Si algo suena raro, lo primero es: **¿qué quise decir y qué escribí?** | La [[99 - Glosario Rápido\|notación errada]] fabrica ecuaciones que no son las que uno tenía en la cabeza |

---

## Conexiones con otras Notas

- **Índice y red**: el mapa completo del curso está en [[00-indice-maestro|la red global]].
- **Vocabulario**: los términos de cada remedio se definen en [[99 - Glosario Rápido|el glosario]].
- **Roadmap**: los temas aún no incorporados están en [[97 - Temas Pendientes por Agregar|el roadmap]].
