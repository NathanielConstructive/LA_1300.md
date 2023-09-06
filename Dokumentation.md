# Projekt-Dokumentation

Mirhan Özden

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 23.08      | 0.0.1   | Man kann erraten und die Geheime Zahl wird ausgesucht |
| 30.8      | 0.0.2     |Während dem Raten gibt es Hilfe und es wird alles abgefangen, was ungültig ist.|

## 1 Informieren

### 1.1 Ihr Projekt

In meinem Projekt werde ich ein Programm coden, wo man eine zufällige Zahl erraten muss.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
|1|muss|funktional|Als Benutzer möchte ich, dass das Programm eine Geheimzahl aussucht, zwischen 1-100.|
|2|muss|funktional|Als Benutzer möchte ich die Zahl erraten können.|
| 3    |  kann               | Rand     | Als ein Benutzer möchte ich ein Geräusch hören, je nachdem ob meine Zahl zu hoch oder zu niedrig ist, damit ich ein besseres Gefühl habe, beim erraten.  |
| 4  |  Muss              | Funktional     | Als Benutzer möchte ich bescheid wissen, ob meine gerratene Zahl höher oder niedriger als die Geheimzahl ist, damit ich nicht stundenlang zufällige Zahlen eingeben muss. |
|5|muss|funktional|Als Benutzer möchte ich eine Nachricht bekommen, wenn ich die Geheimzahl erraten habe, damit ich das Spiel fertig spielen kann.|
|6|muss|funktional|Als ein Benutzer möchte ich mehrere Versuche haben, damit ich eine Chance habe, die Zahl zu erraten.|
|7|kann|rand|Als Benutzer möchte ich einen Weissen Hintergrund haben, damit ich beim spielen nicht einschlafe.|
|8|kann|rand|Als Benutzer möchte ich eine schwarze Schriftfarbe haben, damit ich es gut auf dem weissen Hintergrund sehe.|
|9|muss|qualität|Als Benutzer möchte ich, dass das Programm kurz stoppt, falls ich etwas Ungültiges eingebe und mir sagt, dass es ungültig ist, damit nichts anderes passiert, wie zum Beispiel dass das Programm abstürzt. |
|10|kann|Rand|Als Benutzer möchte ich, dass das Programm mir meine Versüche und meinen Namen am Schluss aufzeigt, damit ich mich mit meinen Freunden messen kann.|

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
|1.1|Die Zahl wird ausgesucht|-|-|
|2.1|Eine Zahl wird eingegeben|4|-|
|3.1|Zahl wird erraten|50(Die Zahl ist grösser als die Geheimzahl)|Ein hohes Piepsen kommt, da die Geheimzahl höher ist.|
|4.1|Eine zu nierige Zahl wird eingegeben|40|Eine Nachricht kommt, wo es sagt, dass die Geheimzahl noch höher ist und dass die eingegebene Zahl zu niedrig ist.|
|5.1  | Eine gültige und richtige Zahl wird erraten |  Die Zahl "20"       |    Die Geheimzahl wurde erraten. |
|6.1   | Mehrere Versüche sind möglich | eine gültig aber falsche Zahl(40)        |  "Gib deine Vermutung ein"                 |
|7.1|Die Hintergrundfarbe wird geändert|-|ein weisser Hintergrund|
|8.1|Die Schriftfarbe wird schwarz|-|eine schwarze Schrift|
|9.1|Eine ungültige Eingabe wird eingegeben.|Ungültige Eingabe(Hallo)|Bitte gib eine gültige Zahl ein. Gib deine Vermutung ein:|
|10.1|Das Spiel ist abgeschlossen|die richtige Zahl und der Name|Highscore List: Player: Mirhan, Attempts: 5|

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 23.8     |  Mirhan Özden          |  Geheimzahl wird ausgesucht.            |    45 Minuten           |
| 2.A  | 23.8     | Mirhan Özden           |  Zahl kann eingegeben werden            |   20 Minuten            |
| 3.A  | 23.8     |  Mirhan Özden          |  Geheimzahl kann erraten werden            |  30 Minuten             |
| 4.A  | 23.8     |  Mirhan Özden          |   Falls eingegebene Zahl zu grösser oder zu niedrig ist, wird dies gesagt           |   45 minuten            |
| 5.A  | 23.8     |  Mirhan Özden          | Erkennen ob eine Zahl erraten wurde             |   45 Minuten            |
| 6.A  | 30.8     |  Mirhan Özden          |  Mehrmals Zahlen eingeben            |  40 Minuten             |
| 7.A  | 30.8     |  Mirhan Özden          |   Hintergrundfarbe ist weiss           | 5 Minuten              |
| 8.A  | 30.8     |  Mirhan Özden          |   Schriftfarbe ist schwarz           |  5 Minuten             |
| 9.A  | 30.8     |  Mirhan Özden          |  Falsche Eingaben werden abgefangen            |  50 Minuten             |
|10.A  | 30.8     |  Mirhan Özden          |   Name und Highscore wird angezeigt           |   50 Minuten            |

Total: 10

## 3 Entscheiden

Ich habe mich entschieden, ein Spiel zu programmieren, wo es darum geht eine Zahl zu erraten. Zum erraten gibt es Hilfe vom Program. Wie zum Beispiel ein Ton, je nachdem ob die eingegebene Zahl zu hoch oder zu niedrig ist. Es kommt auch ein Text vor, der sagt ob man zu hoch geraten hat oder zu niedrig. Schliesslich wenn man die Zahl erraten hat, kann man den Namen eingeben und man sieht die Highscoreliste.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |  23.8      |  Mirhan         |    45 Minuten            |      50 Minuten             |
| 2.A  |  23.8      |   Mirhan         |   20 Minuten            |       25 Minuten            |
| 3.A  |  23.8      |  Mirhan          |   30 Minuten            |       35 Minuten            |
| 4.A  |  23.8      |  Mirhan          |    45 minuten           |       40 Minuten            |
| 5.A  |  23.8     |   Mirhan         |    45 minuten           |        40 Minuten           |
| 6.A  |  30.8     |   Mirhan         |     40 Minuten           |       30 Minuten            |
| 7.A  |  30.8     |   Mirhan         |       5 Minuten         |        5 Minuten           |
| 8.A  |  30.8     |   Mirhan         |       5 Minuten         |        5 Minuten           |
| 9.A  |  30.8     |   Mirhan         |       50 Minuten        |       50 Minuten            |
| 10.A  |  30.8     |   Mirhan         |      50 Minuten         |      50 Minuten             |

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 06.09      |  funktioniert        | Mirhan       |
| 2.1  | 06.09       |  funktioniert        |  Mirhan       |
| 3.1  | 06.09       |  funktioniert        |  Mirhan       |
|4.1  | 06.09       |    funktioniert      |   Mirhan      |
| 5.1  | 06.09       |  funktioniert        |   Mirhan      |
|6.1 | 06.09       |    funktioniert      |   Mirhan      |
| 7.1  | 06.09       |  funktioniert        |   Mirhan      |
|8.1 | 06.09       |  funktioniert        |   Mirhan      |
| 9.1  | 06.09       |  funktioniert        |    Mirhan     |
| 10.1 | 06.09       |  funktioniert        |    Mirhan     |
