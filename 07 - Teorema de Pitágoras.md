---
title: "07 - Teorema de Pitágoras"
tags: [geometria, pitagoras, triangulos-rectangulos, demostracion-geométrica]
aliases: [Teorema de Pitágoras, $h^2 = a^2 + b^2$]
type: concept
---

# 07 - El Teorema de Pitágoras

> [!ABSTRACT] Enunciado
> En todo triángulo rectángulo (aquel que posee un ángulo recto de $90^\circ$ o $\frac{\pi}{2}$ radianes), el cuadrado de la hipotenusa es igual a la suma de los cuadrados de los catetos:
> $$h^2 = a^2 + b^2$$

---

## 1. Demostración Geométrica por Áreas

Consideremos un cuadrado exterior de lado $(a + b)$ que inscribe a un cuadrado interior inclinado de lado $h$ (hipotenusa), formando 4 triángulos rectángulos iguales de catetos $a$ y $b$:

![[figuras/pitagoras.svg|523]]

El área total del cuadrado exterior puede calcularse de dos formas equivalentes:

1. **Como área del cuadrado exterior**: $(a + b)^2$.
2. **Como la suma del cuadrado interior más 4 triángulos**:
   $$h^2 + 4 \cdot \left( \frac{a \cdot b}{2} \right) = h^2 + 2ab$$

Igualando ambas expresiones:
$$(a + b)^2 = h^2 + 2ab$$

Desarrollando el lado izquierdo mediante la identidad del [[03 - Cuadrado de un Binomio|cuadrado de binomio]]:
$$a^2 + 2ab + b^2 = h^2 + 2ab$$

Restando $2ab$ a ambos lados:

> [!THEOREM] Teorema de Pitágoras
> $$h^2 = a^2 + b^2 \implies h = \sqrt{a^2 + b^2}$$

---

## Conexiones con otras Notas

- **Fundamento Algebraico**: Requiere la demostración del [[03 - Cuadrado de un Binomio|cuadrado de binomio]] y de [[02 - Propiedad Distributiva|la distributiva]].
- **Extensión Trigonometrica**: Es la base de la identidad fundamental en [[08 - Trigonometría y Circunferencia Unitaria|el círculo unitario]] ($\sin^2 \alpha + \cos^2 \alpha = 1$).
