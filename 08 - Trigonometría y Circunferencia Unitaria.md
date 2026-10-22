---
title: "08 - Trigonometría y Circunferencia Unitaria"
tags: [trigonometria, circulo-unitario, seno, coseno, radianes, teoremas]
aliases: [Trigonometría, Círculo Unitario, Teorema del Seno, Teorema del Coseno]
type: concept
---

# 08 - Trigonometría y Circunferencia Unitaria

> [!ABSTRACT] Medición de Ángulos
> - **Grados Sexagesimales**: Dividen la vuelta completa en $360^\circ$.
> - **Radianes**: Miden el ángulo mediante la longitud del arco de circunferencia recorrido al colocar el radio $R$ sobre el borde. La vuelta completa mide $2\pi$ radianes ($\approx 6.28 R$).

---

## 1. Definición en la Circunferencia Unitaria ($R = 1$)

Dado un punto $P(x, y)$ sobre una circunferencia de radio $R = 1$ centrado en el origen, asociado a un ángulo $\alpha$:

- **$\cos(\alpha)$**: Es la coordenada $x$ del punto terminal $P$.
- **$\sin(\alpha)$**: Es la coordenada $y$ del punto terminal $P$.
- **$\tan(\alpha)$**: Es el cociente $\frac{\sin(\alpha)}{\cos(\alpha)} = \frac{y}{x}$.

Aplicando el [[07 - Teorema de Pitágoras]] al triángulo rectángulo de catetos $x, y$ e hipotenusa $R=1$:
$$\cos^2(\alpha) + \sin^2(\alpha) = 1$$

![[figuras/circulo-unitario.svg]]

---

## 2. Teorema del Seno y Teorema del Coseno

Para **cualquier** triángulo de lados $a, b, c$ y ángulos opuestos $\alpha, \beta, \gamma$:

### Teorema del Seno
$$\frac{a}{\sin(\alpha)} = \frac{b}{\sin(\beta)} = \frac{c}{\sin(\gamma)}$$
*Se demuestra trazando la altura $h$ y dividiendo el triángulo en dos triángulos rectángulos.*

### Teorema del Coseno
$$c^2 = a^2 + b^2 - 2ab \cos(\gamma)$$
*Generalización del [[07 - Teorema de Pitágoras]] para triángulos no rectángulos.*

---

## Conexiones con otras Notas

- **Bases geométricas**: Se apoya directamente en el [[07 - Teorema de Pitágoras|teorema de Pitágoras]].
- **Relación funcional**: Da origen a las [[10 - Funciones y Probabilidades|funciones trigonométricas]].
