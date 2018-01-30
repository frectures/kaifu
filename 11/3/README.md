## Termin 3

### 3.1

Schaue dir die Klasse `TextAnalyse` des Projekts [Iteration](https://github.com/frectures/kaifu/blob/master/11/3/Iteration.zip?raw=true) an. Dort gibt es eine vorgegebene Methode `istFrage(String text)`, die demonstriert, wie man die Länge eines Strings erhält und wie man auf einzelne Zeichen eines Strings zugreift. Probiere diese Methode interaktiv aus, indem du ein Exemplar von `TextAnalyse` erstellst und dann `istFrage` z.B. mit dem aktuellen Parameter `"Wie geht's?"` aufrufst.

Vergleiche die Methoden `istFrage` und `istFrageKompakt`. Worin unterscheiden sie sich?

Was passiert, wenn du der Methode `istFrage` den leeren String als aktuellen Parameter übergibst, also `istFrage("")?` Implementiere eine Lösung, die diesen Fall sinnvoll behandelt.

### 3.2

Schreibe nun eine eigene Methode `int zaehleVokale(String text)`, die für einen gegebenen Text als Ergebnis liefern soll, wie viele Vokale er enthält. Für den String `"Rhabarber"` soll die Methode beispielsweise 3 zurückgeben. Verwende in der Implementierung einen Schleifenzähler, der bei 0 beginnt und alle Positionen des Strings durchläuft.

Die eigentliche Prüfung auf einen Vokal lässt sich entweder mit einer Kette von `if/else if/else if...`-Anweisungen oder mit einer `switch`-Anweisung lösen. Falls du die `switch`-Anweisung nicht kennst, recherchiere eigenständig, indem du `Java switch` in eine Suchmaschine deiner Wahl eintippst.

### 3.3

Schreibe eine weitere Methode `boolean istPalindrom(String text)`, die nur für Palindrome wie anna, otto, regallager oder axa *true* liefert. Vergleicht dazu die passenden Zeichen innerhalb des Strings.

### 3.4

Verwende die Methode `toLowerCase()` aus der Klasse `String`, um den Unterschied zwischen Groß- und Kleinschreibung zu ignorieren, damit auch Anna, Otto und Regallager als Palindrome erkannt werden.