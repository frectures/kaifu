## Termin 1

### 1.1

Lade das Projekt [Ampeln](https://github.com/frectures/kaifu/blob/master/11/Ampeln.zip?raw=true) herunter und studiere die Klasse `Ampel`. Zeichne alle 4 in Hamburg üblichen Ampelphasen für den Kraftverkehr in der richtigen Reihenfolge auf.

### 1.2

Im `Ampel`-Konstruktor wird nur eines der drei booleschen Felder initialisiert. Warum ist es technisch nicht notwendig, die anderen beiden Felder zu initialisieren? Füge von Hand explizite Initialisierungen hinzu, um die Lesbarkeit des Quelltexts zu erhöhen.

### 1.3

Analysiere die Rümpfe der drei Methoden `leuchtetRot`, `leuchtetGelb` und `leuchtetGruen` und überzeuge dich von ihrer softwaretechnischen Äquivalenz. Warum sind weder der Vergleich mit `true` in `leuchtetRot` noch die beiden Fallunterscheidungen in `leuchtetRot` und `leuchtetGelb` notwendig?

### 1.4

Die Methode `schalteWeiter` funktioniert im Auslieferungszustand lediglich für den Wechsel von der ersten in die zweite Phase. Vervollständige den Methodenrumpf für alle vier Phasenwechsel. Teste die Methode, indem du ein `Ampel`-Exemplar erzeugst, dieses per Doppelklick mit dem Objektinspektor öffnest und anschließend vier Mal weiterschaltest.

Optisch ansprechender ist das Testen nach der Erzeugung eines Exemplars von `AmpelGUI`. Hier wird per Knopfdruck auf "weiter" in die nächste Ampelphase geschaltet.

### 1.5

Die Klasse `Bmpel` besitzt keine booleschen Felder für die Lampen, sondern verwendet stattdessen ein `int`-Feld, welches periodisch die Werte 0, 1, 2, 3 durchläuft. Ein Testen mit dem Objektinspektor ist jetzt nicht mehr sinnvoll, aber dafür gibt es ja die Klasse `BmpelGUI`. Die Implementation der `schalteWeiter`-Methode ist im Vergleich mit den vorherigen Lösungen trivial. Schaue dir ihren Rumpf an und probiere in der BlueJ-Direkteingabe (mit Strg+E aktivierbar) aus, was die Formel `(x + 1) % 4` für verschiedene `x` bewirkt.

### 1.6

Die drei Methoden zur Abfrage der Lampen gestalten sich jetzt etwas umfangreicher, da das Ergebnis nicht bereits in einem Feld vorliegt, sondern erst berechnet werden muss. Die Methode `leuchtetGruen` ist schon fertig implementiert. Vervollständige die Rümpfe der anderen beiden Methoden.

### 1.7

Die Klasse `Zmpel` kommt vollständig ohne Fallunterscheidungen aus. In der Methode `schalteWeiter` wird der Folgezustand direkt aus dem aktuellen Zustand berechnet, indem die Felder mit passenden booleschen Operatoren verknüpft werden. Die Berechnung des Folgezustands der grünen Lampe ist bereits implementiert. Ergänze den Methodenrumpf für die anderen beiden Lampen. Mache dir bei Bedarf anhand einer Tabelle klar, wie der Folgezustand vom aktuellen Zustand abhängt.
