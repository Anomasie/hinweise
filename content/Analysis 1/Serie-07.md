---
title: "Serie 7"
date: 2025-12-11T12:29:00+01:00
draft: false
---

# Aufgabe 2

## (a) $n + 1_K \neq 1_K$

- {{< details >}} Ihr könnt zum Beispiel zeigen, dass alle Elemente aus $\mathbb N_K$ in $K_+$ liegen. {{</ details >}}

- {{< details >}} Das liegt daran, dass es eine induktive Menge gibt, deren Elemente allesamt größer sind als null. {{</ details >}}

## (b) Peano-Axiome

**Achtung**: Frühere Aufgaben zu $\mathbb N$ setzten bereits voraus, dass die Peano-Axiome gelten. Das $\mathbb N_K$ aus dieser Aufgabe ist allerdings auf eine neue Art definiert. Ihr könnt also nicht diejenigen früheren Übungsaufgaben benutzen, die voraussetzen, dass die Axiome gelten.

### Injektivität

- {{< details >}} Das folgt aus $0_K \neq 1_K$. {{</ details >}}

### Induktivität

- {{< details >}} Zu zeigen ist, dass eine induktive Teilmenge von $\mathbb N_K$ auch eine Obermenge von $\mathbb N_K$ sein muss. {{</ details >}}

- {{< details >}} $\mathbb N_K = \bigcap_{A \subseteq K \text{ induktiv}} A$ {{</ details >}}

## (c) $J(\mathbb N) = \mathbb N_K$

- {{< details >}} Ich würde beide Inklusionen zeigen. **Schritt 1** sei $J(\mathbb N) \subseteq \mathbb N_K$, **Schritt 2** sei die andere Inklusion. {{</ details >}}

### Schritt 1

- {{< details >}} $\mathbb N_K$ ist der Schnitt aller induktiven Mengen. Also ist $X$ eine Teilmenge von $\mathbb N_K$, wenn $X \susbeteq A$ für alle induktiven Mengen $A$ gilt. {{</ details >}}

- {{< details >}} Es reicht also zu zeigen, dass $J(\mathbb N)$ eine Teilmenge jeder induktiven Menge $A$ sein muss. {{</ details >}}

- {{< details >}} Das geht zum Beispiel über Induktion über die $n \in \mathbb N$, für die $J(n)$ in $A$ liegt. {{</ details >}}

### Schritt 2

- {{< details >}} $\mathbb N_K$ ist der Schnitt aller induktiven Mengen. Also eine Teilmenge all dieser Mengen. {{</ details >}}

- {{< details >}} Es reicht also ist zu zeigen, dass $J(\mathbb N)$ induktiv ist. {{</ details >}}

# Aufgabe 3

In dieser Aufgabe ist es wichtig, dass ihr genau begründet, wieso die Eigenschaften für "Diese Folge konvergiert gegen diesen Wert" erfüllt sind.
Ihr könnt auch auf Aussagen aus der Vorlesung zurückgreifen.

## (a) $\lim_{n \to \infty} \frac{(n+1)^2 - n^2}n = 2$

- {{< details >}} Vereinfachen des Terms führt zu: {{</ details >}}

- {{< details >}} $\frac{(n+1)^2 - n^2}{n} = 2 + \frac 1 n$. {{</ details >}}

- {{< details >}} Wenn ihr zeigen wollt, dass $\frac 1 n$ gegen $0$ konvergiert für $n \to \infty$, dann benötigt ihr das archimedische Axiom. {{</ details >}}

## (b) $\lim_{n \to \infty} \frac n {2^n} = 0$

- {{< details >}} Ich würde zuerst $2^n$ nach unten abschätzen, also einen passenden Term $\dots$ finden mit $\ldots \leq 2^n$. {{</ details >}}

- Hilfsaussage:

    - {{< details >}} Ihr könnt zum Beispiel zuerst zeigen, dass $n (n-1) \leq 2^n$ gilt. {{</ details >}}

    - {{< details >}} Induktion über $n$. {{</ details >}}

    - {{< details >}} Für $n = 1$ und $n = 2$ lässt es sich ausrechnen. Für $n \geq 3$ gilt (wieso?) $2(n-1) \geq n+1$. {{</ details >}}

- {{< details >}} Anschließend könnt ihr $0 \leq \left| \frac n {2^n} \right| \leq \left| \frac 1 {n-1} \right|$ benutzen. {{</ details >}}

## (c) $\lim_{n \to \infty} \frac {1+2^3 + \dots + n^3}{n^4} = \frac 1 4$

- Zeigt zuerst, wie im Hinweis steht, $$\sum_{k=1}^n k^3 = \frac 1 4 n^2 (n+1)^2 .$$

- {{< details >}} Das ist ein klassischer Induktionsbeweis. Danach: {{</ details >}}

- {{< details >}} Nun könnt ihr die Terme vereinfachen. {{</ details >}}

- {{< details >}} Das Ergebnis sollte $\frac {1+2^3 + \dots + n^3}{n^4} = \frac 1 4 \left( 1 + 2 \frac 1 n + \frac 1 {n^2} \right)$ sein. {{</ details >}}

- {{< details >}} Seht euch die Terme einzeln an und benutzt den Satz über den Zusammenhang von Summen und Konvergenzen. Dann müsst ihr noch drei Aussagen zeigen: {{</ details >}}

- {{< details >}} $1 \to 1$, $\frac 1 n \to 0$ und $\frac 1 {n^2} \to 0$ für $n \to \infty$, {{</ details >}}

- {{< details >}} Ihr könnt von $n \geq 1$ ausgehen, also ist $|\frac 1 {n^2}| \leq |\frac 1 n|$. {{</ details >}}

# Aufgabe 4: $\lim_{n \to \infty} x_n = 0$ und $\lim_{n \to \infty} y_n = \infty$ mit:

Ihr müsst, selbstverständlich, in jedem Fall auch beweisen, dass eurer Beispiel gegen den gewünschten Wert konvergiert bzw. nicht konvergiert aber beschränkt ist.
(Es ist also von Vorteil, einfache Folgen zu finden.)

## (a) $\lim_{n \to \infty} x_n \cdot y_n = 0$

- {{< details >}} $0 \cdot y = 0$ für alle $y \in K$. {{</ details >}}

## (b) $\lim_{n \to \infty} x_n \cdot y_n = 1$

- {{< details >}} Betrachte $x_n = \frac 1 {n^a}$, $y_n = n^b$ für geeignete $a, b \in \mathbb N$. {{</ details >}}

## (c) $\lim_{n \to \infty} x_n \cdot y_n = \infty$

- {{< details >}} Betrachte $x_n = \frac 1 {n^a}$, $y_n = n^b$ für geeignete $a, b \in \mathbb N$. {{</ details >}}

## (d) $(x_n \cdot y_n)_{n \in \mathbb N}$ beschränkt, nicht konvergent

- {{< details >}} Überlegt euch zuerst eine Folge, die nicht konvergiert, aber beschränkt ist. {{</ details >}}

- {{< details >}} Das kann passieren, wenn die Folge zwischen mehreren Werten "springt". {{</ details >}}

- {{< details >}} Vermutlich könnt ihr dann $x_n = \text{eure Folge} \cdot \frac 1 n$ und $y_n = n$ wählen. {{</ details >}}
