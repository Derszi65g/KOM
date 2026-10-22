---
title: "03 - Cuadrado de un Binomio"
tags: [algebra, cuadrado-de-binomio, identidades, pilar-matematico]
aliases: [Cuadrado de un Binomio, Identidad Quadrática, (a+b)^2]
type: concept
---

# 03 - Cuadrado de un Binomio

> [!ABSTRACT] Definición
> El cuadrado de un binomio no es una fórmula para memorizar: es una **identidad demostrable** a partir de la [[02 - Propiedad Distributiva]]. Expresarla como identidad — y no como receta — es lo que permite usarla "al revés" al resolver ecuaciones cuadráticas.

---

## 1. La Identidad

$$(a + b)^2 = a^2 + 2ab + b^2$$

El error clásico es creer que $(a+b)^2 = a^2 + b^2$. Esa equivocación desaparece cuando se entiende que el cuadrado aplica la distribución completa:

$$(a + b)^2 = (a + b)(a + b) = a\cdot a + a \cdot b + b \cdot a + b \cdot b$$

Los dos términos cruzados $ab$ y $ba$ son iguales por conmutatividad, de modo que $2ab$ no es un "extra mágico": es la suma de los dos productos cruzados.

---

## 2. Demostración Geométrica

Se construye un cuadrado de lado $(a + b)$ y se divide en cuatro regiones:

- Un cuadrado de área $a^2$ (esquina superior izquierda).
- Un cuadrado de área $b^2$ (esquina inferior derecha).
- Dos rectángulos de área $a \cdot b$ cada uno.

La superficie total es la suma de las cuatro regiones:

$$a^2 + ab + ab + b^2 = a^2 + 2ab + b^2$$

EstaVisualización muestra que la identidad es una verdad estructural, no una convención algebraica.

---

## 3. Uso Inverso: Completar el Cuadrado

Leer la identidad de derecha a izquierda es la base de la **completación de cuadrados**, el paso clave para deducir [[05 - Ecuaciones Cuadráticas y Bhaskara|la fórmula general de la cuadrática]]:

$$x^2 + bx + \left(\tfrac{b}{2}\right)^2 = \left(x + \tfrac{b}{2}\right)^2$$

---

## 4. Conexiones

- **Fundamento**: Se deriva directamente de la [[02 - Propiedad Distributiva|distributiva]].
- **Deducción de la fórmula cuadrática**: Usada en sentido inverso en [[05 - Ecuaciones Cuadráticas y Bhaskara|la resolvente]].
- **Geometría**: Sostiene la [[07 - Teorema de Pitágoras|demostración algebraica de Pitágoras]].
- **Ampliación**: El mismo principio distributivo se extiende al cubo de un binomio y al binomio de Newton.

---
