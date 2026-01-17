---
title: "Serie 09"
date: 2026-01-08T08:53:00+01:00
draft: false
---

# Aufgabe 1

Überlegt euch am besten zuerst, wie $(x_n - y_n)_n$ aussehen soll, und wählt dann $x_n$ und $y_n$ so, dass ihr dieses Ergebnis erhaltet.

# Aufgabe 2

Bitte vergesst nicht, das archimedische Axiom, Vollständigkeit von $\mathbb R$ o. Ä. zu erwähnen, wenn ihr sie benutzt.

# Aufgabe 3

- {{< details >}} Es genügt, (i) $\Rightarrow$ (ii) $\Rightarrow$ (iii) $\Rightarrow$ (iv) $\Rightarrow$ i zu zeigen. {{</ details >}}

{{< details >}} (iii) $\Rightarrow$ (iv) {{</ details >}}

- {{< details >}} Hier müsst ihr eine Teilfolge konstruieren. Das Vorgehen ist ähnlich wie in Präsenzaufgabe A auf diesem Blatt. {{</ details >}}

- {{< details >}} Für jedes $k \in \mathbb N$ müsst ihr also ein $n_k$ finden. Wählt dazu zum Beispiel $C = k$. {{</ details >}}

- {{< details >}} Jetzt gibt es laut (iii) ein solches $x_{n_k}$. {{</ details >}}

- {{< details >}} Zu zeigen ist noch, dass diese Teilfolge bestimmt gegen $\infty$ divergiert. {{</ details >}}

{{< details >}} (iv) $\Rightarrow$ (i) {{</ details >}}

- {{< details >}} Schaut in eure Notizen zur Definition des Limes Superior. In den alten Notizen wurde es zum Beispiel als $\lim_{n \to \infty} \sup ( x_k \mid k \geq n )$ definiert. (Die Klammern sollten selbstverständlich geschwungen sein.) Ihr müsstet also zeigen, dass dieses Supremum bestimmt gegen $\infty$ divergiert. {{</ details >}}

- {{< details >}} Es genügt, $\sup ( x_k \mid k \geq n ) \geq \sup ( x_{n_k} \mid k \geq N )$ zu zeigen. {{</ details >}}

# Aufgabe 4

## $a_n < b_n < c_n$

Wenn ihr die Terme unformt, um zu einer wahren Aussage zu gelangen, setzt die Implikationspfeile in die richtige Richtung (die ihr auch benötigt!).
Besser ist es beim Aufschreiben, von wahren Aussagen, z. B. $a^2 < n$, auszugehen und daraus die gewünschte Aussage herzuleiten.

## $\lim_n a_n = 0$

- {{< details >}} Beginnt mit "Sei $\epsilon > 0$". {{</ details >}}

- {{< details >}} Formt $|a_n| < \epsilon$ geeignet um. Zwischenschritte können z. B. sein: {{</ details >}}

    - {{< details >}} $|a_n| = \sqrt n ( ... ) < \epsilon$ {{</ details >}}

    - {{< details >}} $\sqrt{a + \frac 1 n} < \frac {\epsilon} {\sqrt n} + 1$ {{</ details >}}

    - {{< details >}} $1 + \frac a n < \frac {\epsilon^2} n + 1 + 2 \frac \epsilon {\sqrt n}$ {{</ details >}}

## $\lim_n b_n = \frac 1 2$

Geht vor wie bei $(a_n)_n$. Wenn ihr euch verrechnet, ist das nicht schlimm. Es geht eher darum, dass ihr wisst, wie ihr einen Konvergenzbeweis führt.

## $\lim_n c_n = \infty$

- {{< details >}} Ihr könnt bei $c_n$ den Term $\sqrt n$ ausklammern. {{</ details >}}

- {{< details >}} Genauer ist $c_n = \sqrt n \left( \sqrt{1+\frac 1 a} - 1 \right)$. {{</ details >}}
