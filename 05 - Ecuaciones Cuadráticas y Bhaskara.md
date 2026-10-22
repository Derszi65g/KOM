---
title: "05 - Ecuaciones Cuadráticas y Bhaskara"
tags: [algebra, ecuaciones, cuadraticas, bhaskara, completacion-de-cuadrados]
aliases: [Ecuaciones Cuadráticas, Fórmula de Bhaskara, Completar Cuadrados]
type: concept
---

# 05 - Ecuaciones Cuadráticas y la Fórmula de Bhaskara

> [!ABSTRACT] Definición
> Una ecuación cuadrática o de segundo grado tiene la forma general:
> $$a x^2 + b x + c = 0 \quad (a \neq 0)$$

---

## 1. Método de Completación de Cuadrados

En lugar de memorizar una receta, la ecuación cuadrática se resuelve reescribiendo la expresión para que la incógnita $x$ aparezca una sola vez, utilizando el [[03 - Cuadrado de un Binomio]] en sentido inverso.

Ejemplo con $x^2 + 6x = 3$:
1. Identificamos el término lineal $6x$ como el doble producto $2 \cdot x \cdot 3$.
2. Para formar $(x + 3)^2 = x^2 + 6x + 9$, nos sobra un $9$.
3. Compensamos restando $9$:
   $$(x + 3)^2 - 9 = 3 \implies (x + 3)^2 = 12$$
4. Aplicamos raíz cuadrada a ambos lados:
   $$\sqrt{(x + 3)^2} = \sqrt{12} \implies |x + 3| = \sqrt{12}$$
5. Despejamos $x = -3 \pm \sqrt{12}$.

---

## 2. Demostración de la Fórmula General (Bhaskara)

Partiendo de $a x^2 + b x + c = 0$:

1. Dividimos por $a$ ($a \neq 0$): $x^2 + \frac{b}{a}x + \frac{c}{a} = 0$.
2. Restamos $\frac{c}{a}$: $x^2 + \frac{b}{a}x = -\frac{c}{a}$.
3. Completamos el cuadrado sumando $\left(\frac{b}{2a}\right)^2$ a ambos lados:
   $$\left(x + \frac{b}{2a}\right)^2 - \left(\frac{b}{2a}\right)^2 = -\frac{c}{a}$$
4. Despejamos el término al cuadrado y agrupamos con denominador común $4a^2$:
   $$\left(x + \frac{b}{2a}\right)^2 = \frac{b^2 - 4ac}{4a^2}$$
5. Aplicamos raíz cuadrada y la definición de valor absoluto:
   $$\left|x + \frac{b}{2a}\right| = \frac{\sqrt{b^2 - 4ac}}{2a} \implies x + \frac{b}{2a} = \pm \frac{\sqrt{b^2 - 4ac}}{2a}$$
6. Restamos $\frac{b}{2a}$:

> [!THEOREM] Fórmula de Bhaskara / Resolvente
> $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

---

## Conexiones con otras Notas

- **Herramienta clave**: Se demuestra gracias al [[03 - Cuadrado de un Binomio|cuadrado de un binomio]] y a [[02 - Propiedad Distributiva|la distributiva]].
- **Geometría**: Se utiliza para calcular catetos e hipotenusas [[07 - Teorema de Pitágoras|con Pitágoras]].
- **Modelos**: Representa las raíces en las [[10 - Funciones y Probabilidades|Funciones Cuadráticas]].
