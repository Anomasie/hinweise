---
title: "Serie 05"
date: 2025-11-25T09:08:00+01:00
draft: false
---

# Aufgabe 1

- Der Körper $K$ ist angeordnet. In einer früheren Version des Aufgabenblatts fehlte diese Notiz.

- {{< details >}} Induktion über $n$ {{</ details >}}

- {{< details >}} Im Induktionsschritt lässt sich **nicht** $(1+x)^n \cdot (1+x) \geq (1+x)^n$ verwenden, weil $(1+x)$ in dieser Aufgabe kleiner ist als $0$. {{</ details >}}

- {{< details >}} Stattdessen könnt ihr $(1+x)^n \cdot (1+x) = (1+x)^n + x \cdot (1+x)^n$ verwenden. {{</ details >}}

# Aufgabe 2

Gebt wieder in jedem Schritt an, welches Axiom ihr benutzt.

# Aufgabe 3

Es sind drei Aussagen zu zeigen.

## Existenz einer oberen / unteren Schranke

- Es ist eine Äquivalenz zu zeigen. Ihr könnt entweder beide Richtungen getrennt zeigen oder argumentieren, warum alle Umformungen, die ihr gemacht habt, äquivalent sind.

- {{< details >}} Nehmt an, ihr hättet eine obere Schranke von $M$. Was bedeutet das? {{</ details >}}

- {{< details >}} Findet eine untere Schranke von $-M$. {{</ details >}}

## Existenz des Supremums / Infimums

- Auch hier müsst ihr eine Äquivalenz zeigen. Wenn ihr begründen könnt, wieso alle benutzen Implikationen Äquivalenzen sind, genügt das.

- {{< details >}} Ihr könnt zeigen, dass ihr das Infimum von $-M$ über das Supremum von $M$ *angeben* könnt. Insbesondere existiert es dann. {{</ details >}}

- {{< details >}} Das Supremum ist die kleinste obere Schranke. Das Infimum ist die größte untere. {{</ details >}}

- {{< details >}} Ihr müsst also zeigen, dass für ein kleineres $b < \sup M$ das Element $-b$ keine untere Schranke für $-M$ ist. {{</ details >}}

- {{< details >}} Finde ein Element in $-M$, das kleiner ist als $-b$. {{</ details >}}

## $\sup M = - \inf(-M)$

- {{< details >}} Das habt ihr in den vorigen Schritten eigentlich schon gemacht. (Wieso?) {{</ details >}}

# Aufgabe 4

Achtet darauf, dass für die "Multiplikation" $nx$ *nicht* die Axiome der Multiplikation gelten, weil $\mathbb N$ keine Teilmenge des Körpers ist. Ihr wisst über $\mathbb N$ nur das, was ihr in der Vorlesung über $\mathbb N$ gelernt habt, von $K$ kennt ihr nur die Körperaxiome, und über die Interaktion zwischen $\mathbb N$ und $K$ (also Ausdrücke der Form $nx$) wisst ihr nur das, was in der Aufgabenstellung definiert wurde.

## (a)

- {{< details >}} Induktion über $n$ {{</ details >}}

## (b)

- {{< details >}} Es genügt, drei Fälle zu betrachten: {{</ details >}}

- {{< details >}} $x = 0_K$, $x = 1_K$ und $x \notin \{0_K, 1_K\}$. {{</ details >}}

- Fall 2: {{< details >}} Induktion über $m$. {{</ details >}}

- Fall 3: {{< details >}} Hier müsst ihr zeigen, dass $J$ nicht multiplikativ ist. {{</ details >}}

    - {{< details >}} Es genügt, ein $n$ und ein $m$ zu finden, für das $J(n \cdot m) = J(n) \cdot J(m)$ nicht gilt. {{</ details >}}

    - {{< details >}} Setzt zum Beispiel $n = m = 1_N$ ein. {{</ details >}}

    - {{< details >}} Warum ist $x = x^2$ ein Widerspruch? {{</ details >}}
