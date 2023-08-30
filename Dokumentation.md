# Projekt-Dokumentation

Mirhan Özden

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 23.08      | 0.0.1   | Man kann erraten und die Geheime Zahl wird ausgesucht |
| 30.8      | 0.0.2     |Während dem Raten gibt es Hilfe und es wird alles abgefangen, was ungültig ist.|
|       | 1.0.0   |                                                              |

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
| 1.A  | 23.8      |  Mirhan Özden         |  Geheimzahl wird ausgesucht.            |    45 Minuten           |
| 2.A  |  23.8     | Mirhan Özden           |  Zahl kann eingegeben werden            |   20 Minuten            |
| 3.A  |  23.8     |  Mirhan Özden          |  Geheimzahl wird erraten            |               |
| 4.A  |  23.8     |  Mirhan Özden          |   Falls eingegebene Zahl zu grösser oder zu niedrig ist, wird dies gesagt           |               |
| 5.A  |  23.8     |  Mirhan Özden          |              |               |
| 6.A  |  30.8     |  Mirhan Özden          |              |               |
| 7.A  |  30.8     |  Mirhan Özden          |              |               |
| 8.A  |  30.8     |  Mirhan Özden          |              |               |
| 9.A  |  30.8     |  Mirhan Özden          |              |               |
|10.A|    30.8     |  Mirhan Özden          |              |               |

Total: 10

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.
