## Termin 2

### 2.1

Öffne das BlueJ-Projekt [Uhrenanzeige](https://github.com/frectures/kaifu/blob/master/11/2/Uhrenanzeige.zip?raw=true). Darin findest du eine (unvollständige und deshalb nicht übersetzbare) Klasse `Nummernanzeige`, die du im Editor öffnen und dir erarbeiten sollst. Lies insbesondere den Klassenkommentar sehr genau durch, um die gewünschte Funktionalität der Klasse zu verstehen. Alle Methodenrümpfe der Klasse sind leer. Implementiere nun alle Methoden im Sinne der Kommentare. Teste deine fertige Klasse gründlich!

### 2.2

Füge nun eine Klasse `Uhrenanzeige` hinzu, die die Anzeige einer Digitaluhr mit Stunden und Minuten implementiert. In der Implementierung der Klasse `Uhrenanzeige` sollst du die Klasse `Nummernanzeige` verwenden (ohne sie zu verändern und ohne ihren Quelltext zu kopieren). Das bedeutet, dass du in der `Uhrenanzeige` Exemplare der `Nummernanzeige` erzeugst und dass du mit der Punktnotation Methoden der `Nummernanzeige` aufrufst. Implementiere in der Uhrenanzeige die Methoden `gibUhrzeitAlsString`, `setzeUhrzeit` und `schalteWeiter`. Letztere soll die Uhrenanzeige um eine Minute weiterschalten (die `Uhrenanzeige` wird interaktiv weitergeschaltet, sie ist keine selbstständig laufende Uhr).

### 2.3

Erweitere die Klasse `Uhrenanzeige` um einen Konstruktor, mit dem die gewünschte Uhrzeit gleich beim Erzeugen eines Exemplars dieser Klasse mit angegeben werden kann.
