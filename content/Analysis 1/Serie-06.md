---
title: "Serie 06"
date: 2025-12-03T19:54:00+01:00
draft: false
---

# Aufgabe 1

- Benutzt den Hinweis auf dem Blatt. Ihr müsst allerdings begründen, wieso das genügt.

## abelsche Gruppe bzw. Körper

- {{< details >}} Das $J$ aus dieser Aufgabe ist (wieso?) das gleiche wie vom letzten und vorletzten Blatt. {{</ details >}}

- Abgeschlossenheit bzgl. Addition:

    - {{< details >}} Zu zeigen ist $\pm J(n) \pm J(m) = \pm J(k)$ für ein $k$. {{</ details >}}

- Zum Hinweis:

    - {{< details >}} $\mathbb Z_K$ ist (wieso?) eine Teilmenge des Körpers $K$. {{</ details >}}
    - Wieso? {{< details >}} $J \colon \mathbb N \to K$. {{</ details >}}
    - Warum ist das nützlich? {{< details >}} Die entsprechenden Axiome übertragen sich auf Teilmengen. (Wieso? Vor allem müsst ihr zeigen, dass $0_K$ und $1_K$ in $\mathbb Z_K$ und $\mathbb Q_K$ enthalten sind.) {{</ details >}}

## kleinste Gruppe bzw. kleinster Körper

- {{< details >}} Nehmt an, eine andere Gruppe bzw. ein anderer Körper würde $J(\mathbb N)$ enthalten. {{</ details >}}
- {{< details >}} Welche Elemente muss sie bzw. er dann noch enthalten, um eine abelsche Gruppe bzw. ein Körper zu sein? {{</ details >}}
- {{< details >}} Betrachtet Inversenbildung bzgl. Addition und Multiplikation, Abgeschlossenheit unter Multiplikation. {{</ details >}}

# Aufgabe 2

- In der Aufgabe dürft ihr nur benutzen, was ihr bereits in der Vorlesung gezeigt habt.

- {{< details >}} Der größte Teil der Aufgabe besteht darin, $\sqrt 2 \notin \mathbb Q$ zu zeigen. {{</ details >}}

- {{< details >}} Nehmt dazu an, $\sqrt 2$ läge in $\mathbb Q$. {{</ details >}}

- {{< details >}} Das heißt, $\sqrt 2 = \frac p q$. {{</ details >}}

- {{< details >}} Nehmt nun ohne Einschränkung an, dass $p$ und $q$ nicht den gemeinsamen Teiler $2$ haben. (Wieso lässt sich das arrangieren?) {{</ details >}}

- {{< details >}} Es gilt nun (wieso?) $p^2 = 2 \cdot q^2$. {{</ details >}}

- {{< details >}} Also ist $p^2$ und damit auch $p$ gerade, also $p = 2 \cdot x$. (Wieso?) {{</ details >}}

- {{< details >}} Daraus folgt (wie?) $2 q^2 = 4 x^2$. {{</ details >}}

- {{< details >}} Jetzt ist auch $q$ gerade. Also haben $p$ und $q$ den gemeinsamen Teiler $2$. {{</ details >}}

# Aufgabe 3

- Die Richtigkeit eurer Antwort muss wie immer bewiesen werden.

- $c \neq 0$

    - {{< details >}} Es gibt zwei Fälle: {{</ details >}}

    - {{< details >}} Es kann entweder keine Lösung geben, eine oder genau $2$. Ihr müsst zeigen, dass all diese Fälle eintreten können (also Beispiele finden), und beweisen, dass es keinen dritten Fall gibt. {{</ details >}}

    - {{< details >}} Ihr könnt für die letzte Aussage zeigen, dass für alle Lösungen $x,y$ gilt: $x = y$ oder $x = -y$. {{</ details >}}
    - {{< details >}} Der Grund ist, dass $x-y = 0$ oder $x+y = 0$ gelten muss. {{</ details >}}
    - {{< details >}} Betrachtet dazu $(x-y)(x+y) = x^2 - y^2$. {{</ details >}}
    - Genau eine Lösung: {{< details >}} Zum Beispiel in $\mathbb F_2$ (siehe letzte Übungsblätter) kann es genau eine Lösung geben, da dort 1 = -1 gilt. {{</ details >}}

# Aufgabe 4: $\inf(A+B) = \inf(A) + \inf(B)$

## (a)

- {{< details >}} Die Gleichheit lässt sich zeigen, indem ihr sowohl $\ldots \geq \ldots$ als auch $\ldots \leq \ldots$ zeigt. {{</ details >}}

- {{< details >}} Zu $\geq$: {{</ details >}}
    - {{< details >}} Die Idee ist zu zeigen, dass $\inf A + \inf B$ eine untere Schranke für $A+B$ ist. {{</ details >}}
    - {{< details >}} Betrachtet ein Element aus $A+B$. Ist es kleiner als $\inf(A) + \inf(B)$? {{</ details >}}

- {{< details >}} Zu $\leq$: {{</ details >}}
    - {{< details >}} Betrachtet zum Beispiel eine Zahl $s > \inf(A) + \inf(B)$. Kann dieses $s$ eine untere Schranke für $A+B$ sein? {{</ details >}}
    - {{< details >}} Nein: Es gilt $s - \inf B > \inf A$. Also ist $s - \inf B$ keine untere Schranke für $A$. (Wieso?) {{</ details >}}
    - {{< details >}} Es gibt also ein $a \in A$ mit $a < s - \inf B$. {{</ details >}}
    - {{< details >}} Analog gibt es ein $b \in B$ mit $b < s-a$. {{</ details >}}
    - {{< details >}} Es ist also $a+b < s$. {{</ details >}}

## (b)

- {{< details >}} Betrachtet Mengen, die Elemente aus $K_-$ und $K_+$ enthalten. {{</ details >}}
