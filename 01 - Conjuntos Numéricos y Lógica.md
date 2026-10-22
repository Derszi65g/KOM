---
title: "01 - Conjuntos Numéricos y Lógica"
tags: [logica, conjuntos, numeros, fundamentos]
aliases: [Conjuntos Numéricos, Lógica Proposicional]
type: concept
---

# 01 - Conjuntos Numéricos y Lógica Proposicional

> [!ABSTRACT] Resumen del Tema
> La matemática no es solo hacer cuentas; es un lenguaje para estructurar el pensamiento. En esta nota se abordan las bases de la **lógica de implicación**, la **teoría de conjuntos** y la **necesidad histórica de ampliar los conjuntos numéricos**.

---

## 1. Razonamiento Lógico: El Implicativo ($P \Rightarrow Q$)

Para analizar teoremas y problemas de la vida real, se utiliza la premisa implicativa:
- **Premisa**: "Si pasa $P$, entonces pasa $Q$" ($P \Rightarrow Q$).
- Si sabemos que ocurrió $Q$, **no podemos afirmar** que haya ocurrido $P$, a menos que la relación sea de doble vía ($P \iff Q$).

> [!EXAMPLE] Ejemplo del Curso
> *"Si llueve ($P$), Pedro lleva el paraguas al trabajo ($Q$)."*  
> Si el martes Pedro llevó el paraguas, **no podemos afirmar que haya llovido**, pues pudo llevarlo por otra razón. Para asegurar que llovió, necesitaríamos la equivalencia estricta ($P \iff Q$).

---

## 2. Teoría de Conjuntos: Operaciones Básicas

Un conjunto es una colección de elementos con una propiedad común:
- **Unión ($A \cup B$)**: Elementos que pertenecen a $A$, a $B$ o a ambos.
- **Intersección ($A \cap B$)**: Elementos que pertenecen **simultáneamente** a $A$ y a $B$.

Estas definiciones son fundamentales más adelante para definir la [[10 - Funciones y Probabilidades|probabilidad condicional]].

---

## 3. Construcción de los Conjuntos Numéricos

Cada conjunto surge para solucionar una limitación del conjunto anterior:

1. **Números Naturales ($\mathbb{N}$)**:
   $$\mathbb{N} = \{0, 1, 2, 3, 4, \dots\}$$
   Sirven para **contar**. *(Nota: El $0$ se incluye formalmente por conveniencia algebraica como elemento neutro de la suma).*

2. **Números Enteros ($\mathbb{Z}$)**:
   $$\mathbb{Z} = \{\dots, -3, -2, -1, 0, 1, 2, 3, \dots\}$$
   Surgen ante la imposibilidad de restar un número mayor a uno menor en $\mathbb{N}$ ($3 - 5 = -2$). Representan deudas, subsuelos o direcciones opuestas.

3. **Números Racionales ($\mathbb{Q}$)**:
   $$\mathbb{Q} = \left\{ \frac{a}{b} \;\middle|\; a \in \mathbb{Z}, b \in \mathbb{Z}, b \neq 0 \right\}$$
   Surgen para medir **partes de un entero** (fracciones de pizza, repartos). La suma y multiplicación son cerradas, pero requieren dominar [[02 - Propiedad Distributiva|la distributiva]].

4. **Números Irracionales ($\mathbb{I}$)**:
   Números que **no** pueden escribirse como fracción de dos enteros (ej. $\sqrt{2}, \pi, e$). Surgen en la geometría, como al calcular la diagonal de un cuadrado [[07 - Teorema de Pitágoras|usando Pitágoras]].

5. **Números Reales ($\mathbb{R}$)**:
   $$\mathbb{R} = \mathbb{Q} \cup \mathbb{I}$$
   Permiten medir cualquier longitud o cantidad continua de la realidad.

---

## Conexiones con otras Notas

- Las operaciones en $\mathbb{R}$ responden a [[02 - Propiedad Distributiva|la distributiva]].
- La resolución de ecuaciones sobre $\mathbb{R}$ se analiza con el [[04 - Ecuaciones Lineales y Proporcionalidad|despeje]].
- Las inecuaciones sobre subconjuntos de $\mathbb{R}$ se exploran con [[09 - Inecuaciones y Valor Absoluto|intervalos y desigualdades]].
- Las relaciones de conjuntos $A \cap B$ se aplican en [[10 - Funciones y Probabilidades|probabilidad]].
