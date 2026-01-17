---
title: "Serie 08"
date: 2025-12-17T16:09:00+01:00
draft: false
---

# Aufgabe 1

Seht euch die Definition von Konvergenz sehr genau an.
Die Aufgabe ist nicht schwer, achtet nur darauf, sie logisch richtig aufzuschreiben.

# Aufgabe 2

## (a) $2^k \leq n < 2^{k+1}$

- {{< details >}} Ihr könnt zum Beispiel zeigen, dass es ein maximales $k$ mit $2^k \leq n$ gibt. {{</ details >}}

- Wieso gilt das?

    - {{< details >}} Der Grund ist, dass es ein $\ell \in \mathbb N$ gibt mit $n < 2^\ell$. {{</ details >}}

    - {{< details >}} Für alle $k > \ell$ gilt dann $n < 2^k$. {{</ details >}}

    - {{< details >}} Also gibt es nur endlich viele $k$ mit $2^k \leq n$. {{</ details >}}

    - {{< details >}} Es gibt mindestens ein solches $k$, weil $2^0 = 1_K$ und $\dots$ {{</ details >}}

    - {{< details >}} $\dots$ $n \geq 1_K$ für alle $n \in \mathbb N$, siehe Blatt 7, Aufgabe 2 oder VL {{</ details >}}

## (b) $x_{2^n} = n$

- {{< details >}} Induktionsbeweis über $n$ {{</ details >}}

- Vergesst nicht, (kurz) das "Insbesondere" zu begründen.

## (c) $x_{n+1} - x_n$ ist eine Nullfolge

- Siehe *Hinweis* auf Blatt 7:
> Ein Beweis, der zeigen soll, dass eine Folge gegen einen Grenzwert konvergiert, beginnt stets mit "Sei $\epsilon > 0$."

- {{< details >}} Es gibt für $|x_{n+1} - x_n - 0|$ zwei Fälle zu unterscheiden. {{</ details >}}

- {{< details >}} Die Fälle sind $k(n) = k(n+1)$ und $k(n) \neq k(n+1) = k(n) + 1$. {{</ details >}}

# Aufgabe 3

Vergesst nicht das archimedische Axiom anzugeben, wenn ihr es benutzt!

## $(a_n)$

- {{< details >}} Kürzen und vereinfachen sollte zu dem folgenden Term führen: {{</ details >}}

- {{< details >}} $\frac 1 {m+1-\frac 1 m}$ mit $n+1 \eqqcolon m$. {{</ details >}}

- {{< details >}} Wählt für $\epsilon > 0$ ein $N$ mit $N+1 > \epsilon$. {{</ details >}}

## $(b_n)$

- Antwort: {{< details >}} Diese Folge konvergiert nicht. Sie hat zwei Häufungspunkte (Grenzwerte von Teilfolgen), $\frac 1 2$ und $-\frac 1 2$. {{</ details >}}

- {{< details >}} Ihr könnt zum Beispiel die Proposition benutzen, dass für konvergente Folgen $(x_n)_n$ gilt, dass $(x_n - x_{n+1})$ eine Nullfolge ist. {{</ details >}}

## $(c_n)$

- {{< details >}} Der Trick bei solchen polynomiellen Brüchen i. d. R., die höchste Potenz herauszukürzen, also hier $n^{3}$. Das führt zu {{</ details >}}

- {{< details >}} $c_n = \frac {\frac 3 n + \frac 1 {n^2}}{1 + \frac 1 n - \frac 1 {n^2}}$. {{</ details >}}

- {{< details >}} Betrachtet Zähler und Nenner getrennt und benutzt die Sätze aus der Vorlesung zu Verträglichkeit von Konvergenzen und Verknüpfungen im Körper. {{</ details >}}

# Aufgabe 4

- Wenn eine Aussage nicht zur Konvergenz von $(x_n)_n$ gegen $x$ äquivalent ist, dann solltet ihr das beweisen, z. B. indem ihr ein Beispiel findet, in dem die eine Aussage gilt und die andere nicht.

- Welche passen zusammen?

    - (i) {{< details >}} Diese Aussage ist äquivalent zu $x_n \to x, n \to \infty$. {{</ details >}}

    - (ii) {{< details >}} Auch das ist äquivalent zu der Konvergenz der Folge $(x_n)_n$ gegen den Punkt $x \in \mathbb R$. {{</ details >}}

    - (iii) {{< details >}} Das sollte euch sehr bekannt vorkommen. {{</ details >}}

    - (iv) {{< details >}} Diese Aussage ist stärker als $x_n \to x$. *Zusatz*: Sie gilt nur für $\dots$? {{</ details >}}

    - (v) {{< details >}} Das ist schwächer als Konvergenz, es gibt Folgen, die (v) erfüllen, aber nicht konvergieren, *Zusatz*: und zwar $\dots$? {{</ details >}}
