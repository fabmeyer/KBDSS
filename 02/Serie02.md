# Knowledge-based Decision Support Systems Serie 02
---
## 1.1 Modellieren Sie folgenden Sachverhalt als Semantic Network:

Katzen werden von Menschen häufig als Haustiere gehalten. In der Natur
jagen Katzen Mäuse. Mäuse leben primär auf Feldern und Wiesen.

<img src="1.png"/>

## 1.2 Formulieren sie den gleichen Sachverhalt mit logischen Operatoren.

* **Menschen(Katzen). (HAVE)**
* **Katzen(Mäuse). (HUNT)**
* **Live\_in(X, Felder) :- Mäuse(X). (LIVE\_IN)**
* ∃X : (Mäuse(X) → LIVE-IN(X,Felder))
* **Live\_in(X, Wiesen) :- Mäuse(X). (LIVE\_IN)**
* ∃X : (Mäuse(X) → LIVE-IN(X,Wiesen))



## Description Logic



2.1 Eine Person ist glücklich

∋Person ≡ Glücklich



2.2 Eine Person die ein Hund besitzt ist glücklich

Person ⊓ hasPet.Hund ≡  Glücklich



2.3 Reto besitzt einen Hund und ist glücklich

(Person ⊓ hasPet.Hund ⊓  Glücklich)(Reto)

Falls die oben beschriebene TBox beachtet wird reicht der folgende Ausdruck:

(Person ⊓ hasPet.Hund )(Reto)



2.4 Tanja besitzt eine Katze mag aber keine Hunde

(Person ⊓ hasPet.Katze ⊓ ¬ likesPet.Hund)(Tanja)



2.5 Welches Resultat ergibt folgende Aussage (K=(T,A))

Hunde haben einen Halter.

Wobei der Kontext Hund = Fido und Halter = Alex

Dies heisst dass Alex der Halter von Fido ist

K =(T, A) then K ⊢ HalterVon(Alex, Fido)



