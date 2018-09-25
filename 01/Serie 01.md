# Knowledge-based Decision Support Systems Serie 01
---
## 1. Was soll mit der Applikation realisiert werden, bzw. welcher Mehrwert entsteht aus deren Einsatz?

- Die Kompetenz der UBS bei Beratungsgesprächen erhöhen, bzw. dem Kunden mehr Kompetenz zu demonstrieren (oder vorgaukeln), indem weitere Ratgeber präsent sind
- Den echten Berater beim Beratungsgespräch unterstützen durch:
	- Routinearbeiten und rechnerische Analysen (Fin)
	- Komplexe wirtschaftliche Fragestellungen (Kalt)
	- Höhere Professionalität dank Präsenz digitaler Agenten
- Dadurch effizientere Beratungsgespräche und damit langfristig weniger Kosten

## 2. Welches Wissen ist für die Entscheidungsfindung relevant?

- Je nach Fragestellung unterschiedliches spezifisches Wissen (**Domain Knowledge**) aus den Gebieten der Ökonomie und political Sciences, welches die Grundlage für die Entscheidungsfindung ist
- **Conceptual Knowledge** ist nötig für die Festlegung der Art der Auswertung der Grundinformationen
- **Domain Knowledge** aus dem Gebiet der Mathematik, welches die Auswertung formal beschreibt
- **Domain Knowledge** aus dem Gebiet der Informatik, damit die Auswertung praktisch und effizient durchgeführt werden kann

## Welche Komplexitäten bestehen die den Einsatz solch einer Applikation rechtfertigen?

- Trotz der Ausbildung der Berater kann dieser nicht alle Details der jeweiligen Anlagen der Kunden kennen
- Alle Kennzahlen und Projektionen der Anlagen sind via Fin abrufbereit
- Aktienkurse sind von einer Vielzahl von Variablen abhängig, unter anderem auch positiver und negativer Einstellungen zu den jeweiligen Firmen. Diese Daten sind jedoch nicht direkt abrufbereit. Eine AI könnte Newssites und Social Media analysieren und via Fin dem Berater und dem Kunden präsentieren

## Welche Daten & Datenquellen würden sie für die Umsetzung nutzen?

Strukturierte Datenquellen

- Kundendatenbank der UBS
- Aktiendatenbank der UBS
- Börsenkurse
- Bewertungen von Rating Agenturen
- Offizielle Zahlen von Grossfirmen
- Internet Traffic analyse

Unstrukturierte Datenquellen

- Analyse von Newssites
- Analyse von Social Media


## Gibt es Restriktionen die bei der Wahl der Daten & Datenquellen berücksichtigt werden müssen?

Auf jeden Fall. 

Besonders bei Datenquellen wie 'Kundendatenbank der UBS' spielt der Datenschutz und die Sicherheit der Daten eine sehr grosse Rolle. Es gilt hier zu berücksichtigen, dass solch heikle Daten auch immer mit einer gewissen Verantwortung zusammenhängen und diese Daten nicht ohne geeignete Datenschutz- und Datensicherungsmassnahmen verwendet werden können.

Beim Einsatz von 'Social Media' und 'Newssites' als Datenquellen muss berücksichtigt werden, dass die Datenqualität nicht gewährleistet ist. Newsportale und ganz besonders Social Media veröffentlichen oftmals Daten, die nicht zwingend der Wahrheit entsprechen müssen. Daher müssten diese Daten sorgfältig gewählt und allenfalls bereinigt werden.

Generell muss zudem darauf geachtet werden, dass stets aktuelle Daten für die Applikation verwendet werden. Veraltete Börsenkurse oder Bewertungen könnten zu einer Fehlinformation des Kunden führen.
 