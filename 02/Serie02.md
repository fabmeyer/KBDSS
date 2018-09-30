# Knowledge-based Decision Support Systems Serie 02
---
## 1.1 Modellieren Sie folgenden Sachverhalt als Semantic Network:

Katzen werden von Menschen häufig als Haustiere gehalten. In der Naturjagen Katzen Mäuse. Mäuse leben primär auf Feldern und Wiesen.

<img src="1.png"/>

## 1.2 Formulieren sie den gleichen Sachverhalt mit logischen Operatoren.

* **Menschen(Katzen). (HAVE)**
* **Katzen(Mäuse). (HUNT)**
* **Live\_in(X, Felder) :- Mäuse(X). (LIVE\_IN)**
* ∃X : (Mäuse(X) → LIVE-IN(X,Felder))
* **Live\_in(X, Wiesen) :- Mäuse(X). (LIVE\_IN)**
* ∃X : (Mäuse(X) → LIVE-IN(X,Wiesen))