# NischenLicht
 Files of Android APP "NischenLicht"

Hier hast du die Wahl aus verschiedenen Büchern zufällig generierte Abschnitte zu lesen, so als würdest ein Buch nehmen, irgendwo aufschlagen und das lesen, was vor dir ist. 

Wofür sich die App auch hervorragend eignet, ist das tägliche Lesen in den Bahá'í-Schriften. Es kann eine gute Ergänzung sein zu einem systematischen Ansatz, die Lehren der Bahá'i besser kennenzulernen. 

Die App selbst gibt es als Onlineversion, auf: http://nischenlicht.de

---------------------------------------------

Folgende Bücher stehen bisher zur Verfügung:

- Verse Gottes
- Ährenlese
- Gebete
- Die Verborgenen Worte
- Gebete und Meditationen


Features:

- Light- und Dark-Mode (Button neben Menü)
- Vergrößerung und Verkleinerung des Textes (Pfeile unter dem Text, rechts)

---------------------------------------------

Wer sich für den technischen Ablauf interessiert:

Die Bücher sind als Textdateien gespeichert, wobei jedes Kapitel (oder jeder Abschnitt, je nach Buch) mit einem einzigartigen Zeichen beginnt - hier das @-Zeichen. Gehe ich nun auf eine der Unterseiten, z.B. auf "Verse Gottes", dann wird ein kurzes Javascript-Programm aktiviert. Es sind nur eine Handvoll Zeilen Code. Das Skript sucht in der dazugehörige Textdatei dieAnzahl der @-Zeichen und lässt diese Anzahl durch einen Zufallsalgorithmus laufen. Es kommt eine Ergebnis, eine Zahl dabei heraus (z.B. 19). Dann wird aus der Textdatei der 19. Abschnitt geladen. Tippe ich auf "Weiter", wird die Seite einfach neu geladen und das Skript läuft von neuem durch.

---------------------------------------------

Dies ist nun die 3. Version von NischenLicht. Sie wurde vollständig neu programmiert, bzw. zusammengebaut, mit Hilfe eines Templates, das viele Grundfunktionen schon hatte, wie das Menü und viele Beispielseiten für den mobilen Gebrauch. Alle Teile und Funktionen sind nach langer Recherche und viel 'Try and Error' entstanden. Es basiert auf der Arbeit und dem Wissen von Menschen, die ihre Erfahrung freimütig und offen über das Internet geteilt haben.