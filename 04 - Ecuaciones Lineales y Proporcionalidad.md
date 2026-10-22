---
title: "04 - Ecuaciones Lineales y Proporcionalidad"
tags: [ecuaciones, algebra, lineal, proporcionalidad, regla-de-tres]
aliases: [Ecuaciones Lineales, Proporcionalidad Directa, Regla de Tres]
type: concept
---

# 04 - Ecuaciones Lineales y Proporcionalidad

> [!ABSTRACT] Identidad vs. Ecuación
> - **Identidad / Igualdad**: Se cumple para cualquier valor (ej. $2 + 1 = 3$ o $x = x$).
> - **Ecuación**: Igualdad condicional que contiene una incógnita desconocida $x$. Su objetivo es hallar el valor que satisface la condición.

---

## 1. Estructura y Despeje de una Ecuación Lineal

Toda ecuación de primer grado puede llevarse a la forma canónica:
$$a x + b = 0 \quad (a \neq 0)$$

### Principio de Despeje
No se "pasan" números de un lado a otro mágicamente. Se aplican **operaciones simétricas idénticas en ambos miembros** de la igualdad para mantener el equilibrio cuantitativo:

1. Restamos $b$ a ambos lados:
   $$a x + b - b = 0 - b \implies a x = -b$$
2. Dividimos ambos lados por $a$ ($a \neq 0$):
   $$\frac{a x}{a} = \frac{-b}{a} \implies x = -\frac{b}{a}$$

Para simplificar términos agrupados con paréntesis, aplicamos [[02 - Propiedad Distributiva|la distributiva]].

---

## 2. Proporcionalidad Directa y Regla de Tres

Una relación entre dos magnitudes $x$ e $y$ es **directamente proporcional** si al escalar una por un factor $c$, la otra se escala exactamente en la misma proporción $c$, cumpliendo que $(0,0)$ corresponde al origen:

$$y = c \cdot x$$

Donde $c$ es la **constante de proporcionalidad**.

### Origen Conceptual de la Regla de Tres
Dada la correspondencia $x_1 \to y_1$, si queremos hallar $y_2$ para un nuevo $x_2$:
1. Hallamos el factor de escala: $c = \frac{y_1}{x_1}$.
2. Aplicamos la escala al nuevo valor: $y_2 = c \cdot x_2 = \frac{x_2 \cdot y_1}{x_1}$.

De ahí surge la clásica fórmula mecánica: $y_2 = \frac{x_2 \cdot y_1}{x_1}$.

---

## Conexiones con otras Notas

- **Evolución a 2D**: Al combinar dos ecuaciones lineales dependientes se forman [[06 - Sistemas de Ecuaciones|los sistemas]].
- **Generalización**: La proporcionalidad directa $y = c \cdot x$ es el modelo básico de las [[10 - Funciones y Probabilidades|Funciones Lineales]].
- **Paso a segundo grado**: Cuando la variable se multiplica por sí misma, pasamos a la [[05 - Ecuaciones Cuadráticas y Bhaskara|ecuación cuadrática]].
