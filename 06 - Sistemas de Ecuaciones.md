---
title: 06 - Sistemas de Ecuaciones
tags:
  - algebra
  - sistemas-de-ecuaciones
  - sustitucion
  - igualacion
  - interseccion
aliases:
  - Sistemas de Ecuaciones $2 \times 2$
  - Métodos de Resolución
type: concept
---

# 06 - Sistemas de Ecuaciones Lineales ($2 \times 2$)

> [!ABSTRACT] Concepto
> Un sistema de ecuaciones $2 \times 2$ busca hallar valores simultáneos para dos incógnitas $(x, y)$ que satisfagan dos condiciones de manera simultánea:
> $$\begin{cases} a_1 x + b_1 y = c_1 \\ a_2 x + b_2 y = c_2 \end{cases}$$

---

## 1. Métodos Algebraicos de Resolución

Ambos métodos se derivan de aislar incógnitas aplicando las [[04 - Ecuaciones Lineales y Proporcionalidad|reglas del despeje]].

### A. Método de Igualación
1. Despejamos la misma variable (ej. $y$) en ambas ecuaciones:
   $$y = f_1(x) \quad \text{y} \quad y = f_2(x)$$
2. Igualamos las expresiones ($y = y$): $f_1(x) = f_2(x)$.
3. Resolvemos la ecuación resultante de una sola incógnita $x$.

### B. Método de Sustitución
1. Despejamos una incógnita en una ecuación (ej. $y = 14 - x$).
2. Sustituimos esa expresión en la otra ecuación.
3. Obtenemos una ecuación lineal simple.

---

## 2. Interpretación Geométrica

Cada ecuación lineal representa una **recta** en el plano cartesiano $x$-$y$. Resolver el sistema equivale a hallar el **punto de intersección** $(x, y)$ entre ambas rectas:

- **Sistema Compatible Determinado**: Las rectas se cortan en un único punto $(x, y)$.
- **Sistema Incompatible**: Las rectas son paralelas no coincidentes (incoherencia matemática, ej. $3 = 1$).
- **Sistema Compatible Indeterminado**: Las rectas son coincidentes (infinitas soluciones).

![[figuras/sistema-2x2.svg|700]]

---

## Conexiones con otras Notas

- **Bases**: Cada ecuación individual es una extensión del [[04 - Ecuaciones Lineales y Proporcionalidad|despeje lineal]].
- **Modelación**: Su interpretación gráfica se estudia mediante [[10 - Funciones y Probabilidades|Funciones Lineales]].
