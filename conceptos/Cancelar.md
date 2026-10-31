---
title: "Concepto: Cancelar"
tags: [concepto, algebra, fundamentos, cancelacion]
aliases: [cancelar, cancelación, cancele, cancelado]
type: atom-concept
---

# Cancelar

> [!ABSTRACT] Definición Mínima
> **Cancelar** no es un tachado mágico donde los números desaparecen al azar. Es la **aplicación estricta de un elemento neutro** (el $0$ en la suma o el $1$ en la multiplicación).

---

### Los Dos Tipos de Cancelación

#### 1. Cancelación Aditiva (Neutro $0$)
Se aplica cuando dos [[conceptos/Término|términos]] son opuestos en una suma o resta:
$$a - a = 0 \implies x + 7 - 7 = x + 0 = x$$

#### 2. Cancelación Multiplicativa (Neutro $1$)
Se aplica en una división cuando un [[conceptos/Factor|factor]] se divide por sí mismo:
$$\frac{a}{a} = 1 \implies \frac{5x}{5} = \left(\frac{5}{5}\right) \cdot x = 1 \cdot x = x \quad (a \neq 0)$$

---

### La Gran Regla: Solo Factores, Jamás Términos
* **Válido**:
  $$\frac{a \cdot b}{a \cdot c} = \frac{b}{c} \quad (\text{porque } a \text{ es factor del total})$$
* **Inválido (Error clásico)**:
  $$\frac{a + b}{a} \neq b$$
  El sumando $a$ es un término de la suma, no un factor de toda la expresión.

---

### Notas Relacionadas
* Base teórica: [[01.1 - Estructura Algebraica: Términos, Factores y Simplificación]]
* Catálogo de trampas: [[98 - Errores Comunes]]
* Requisito previo para cancelar: [[conceptos/Factorizar]]
