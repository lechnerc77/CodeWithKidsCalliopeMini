# Code With Kids - Übungen und Musterlösungen für den Calliope Mini
Dieses Repository enthält die Musterlösungen zu einigen Übungen für den [Calliope Mini 2017](https://www.calliope.cc/).
Die Übungen sind für die ersten Programmiererfahrungen von Kindern ab der dritten Klasse gedacht.

In diesem README File werden die einzelnen Aufgabenstellungen kurz beschrieben. Die Lösungen sind im Repository in zwei Formen verfügbar:
* Als XML-Datei zum Import in den [Open Roberta Lab Editor](https://lab.open-roberta.org/) 
* Als HEX Datei zum direkten Aufspielen auf den Calliope Mini

## Übungsbeschreibung
### Der Calliope Mini als Klavier

Programmiere ein Mini-Klavier mit Hilfe der Pins des Calliope Mini. Je nachdem welchen Pin Du beim Calliope Mini gedrückt hälst, soll ein anderer Ton gespielt werden.

**Tipp:** Überlege erst wie der Ablauf aussehen soll.

Die zugehörigen Dateien sind:
* `Klavier.hex`
* `Klavier.xml`

### Der Calliope Mini als Klavier (erweitert)

Erweitere das Mini-Klavier: neben dem Ton, soll nun auf dem LED auch die zugehörige Note angezeigt werden.

Die zugehörigen Dateien sind:
* `Klavier_komplett.hex`
* `Klavier_komplett.xml`

### Der Calliope Mini als Würfel

Simuliere mit dem Calliope Mini einen Würfel: 
* Wenn Du die Taste A drückst, dann soll ein Würfelergebnis am LED Bildschirm erscheinen (wie bei einem richtigen Würfel
* Das Ergebnis des Würfels ist nichts anderes als eine Zufallszahl zwischen 1 und 6

Wir teilen die Aufgabe in zwei Schritte auf

#### Schritt 1

Zeige in einem ersten Schritt eine Zufallszahl zwischen 1 und 6 auf dem LED Bildschirm des Calliope Mini an.

Die zugehörigen Dateien sind:
* `Wuerfel_einfach.hex`
* `Wuerfel_einfach.xml`

#### Schritt 2

Nachdem wir nun wissen, wie wir eine ZUfallszahl ermitteln und ausgeben, zeigen wir anstelle der Zahl nun die Würfelaugen auf dem LED Bildschirm an.

**Tipp:** Der Calliope muss sich die Zahl merken. Damit er dies kann, musst Du ihm einen Bereich geben, wo er das Ergebnis speichern kann. Dies nennt man Variable.

Die zugehörigen Dateien sind:
* `Wuerfel_komplett.hex`
* `Wuerfel_komplett.xml`

### Der Calliope Mini als Rechentrainer

Der Calliope Mini soll Dir Rechenaufgaben aus dem 
1x1 stellen:
* Wenn Du die Taste A drückst, soll auf dem LED Bildschirm eine Rechenaufgabe als Text erscheinen.
* Wenn Du die Taste B drückst, soll auf dem LED Bildschirm das Ergebnis als Text erscheinen.

Wir teilen die Aufgabe in zwei Schritte auf. 

#### Schritt 1 

In einem ersten Schritt wollen wir fest das eine Rechenaufgabe und ein Ergebnis ausgeben. Nehmen wir zum Beispiel `3 x 7`

Die zugehörigen Dateien sind:
* `Rechentrainer_start.hex`
* `Rechentrainer_start.xml`

#### Schritt 2

In zweiten Schritt wollen wir die fixen Werte aus Schritt 1 durch Zufallszahlen ersetzen und so einen richtigen Rechntrainer programmieren.

Die zugehörigen Dateien sind:
* `Rechentrainer_komplett.hex`
* `Rechentrainer_komplett.xml`

### Der Calliope Mini als Alarmanlage

Wir wollen den Calliope Mini als Alarmanlage benutzen. Dafür nutzen wir den Helligkeitssensor.

Die Alarmanlage soll einen Ton ausgeben und die RGB LED soll rot leuchten, wenn der Helligkeitswert einen bestimmten Grenzwert übersteigt. Ansonsten soll die RGB LED grün leuchten

Wir teilen die Aufgabe in drei Schritte auf. 

#### Schritt 1

Erstelle ein Programm mit dem Du die Helligkeit des Sensors auf dem LED Bildschirm anzeigst. Probiere aus welche Werte der Calliope anzeigt (Hell, Dunkel)

Die zugehörigen Dateien sind:
* `Lichtmessung_einfach.hex`
* `Lichtnessung_einfach.xml`

#### Schritt 2

Wir kennen nun die typischen Werte, die der Calliope Mini misst, wenn es hell oder dunkel ist. Erweitere das Programm, so dass der Helligkeitswert nur angezeigt wird, wenn er über dem Wert im Dunkeln liegt.

#### Schritt 3

Wir bauen nun die Alarmanlage fertig. Anstelle der Anzeige der Helligkeit auf dem LED Bildschirm, soll:
* Die LED Lampe rot leuchten
* Ein Ton gespielt werden

Ansonsten soll die LED Lampe grün leuchten

Die zugehörigen Dateien sind:
* `Alarmanlage_komplett.hex`
* `Alarmanlage_komplett.xml`

### Der Calliope Mini als Ideengeber

Wir wollen eine Geschichte schreiben, haben aber keine Idee, was wir schreiben sollen :-( 

Lass uns den Calliope Mini so programmieren, dass er uns ein paar zufällige Bilder zeigt, die uns Ideen geben und beim Schreiben der Geschichte helfen.

Programmiere den Calliope Mini so, dass er auf dem LED Bildschirm ein zufälliges Bild anzeigt und nach zwei Sekunden den zugehörigen Text.

**Tipp:** Du musst in den Expertenmodus des Editors wechseln, damit Du mit Listen arbeiten kannst

Die zugehörigen Dateien sind:
* `Ideengeber.hex`
* `Ideengeber.xml`