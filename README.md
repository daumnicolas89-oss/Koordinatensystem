# Ferien-Koordinaten

Live-Koordinatensystem für die Teamsitzung: Wie hat die Ferienbetreuung geklappt,
und wie wichtig war das jeweilige Thema für die eigene Arbeit?

Gedacht fürs Smartboard — die Leitung trägt während der Sitzung ein, das Team sieht
das Bild live entstehen.

## Öffnen

`index.html` im Browser öffnen. Keine Installation, kein Server, keine Internetverbindung nötig.

## Bedienung

1. Rechts ein Kriterium antippen.
2. In die Fläche tippen — der Punkt wird gesetzt.
3. Weitere Meinung zum selben Kriterium? Nochmal tippen — es entsteht ein zweiter Punkt.
4. Korrigieren: Punkt einfach verschieben.

Nach dem ersten Punkt springt die Auswahl automatisch aufs nächste offene Kriterium.

| Schaltfläche | Funktion |
|---|---|
| Einzelstimmen | Alle Einzelpunkte dauerhaft einblenden (sonst nur beim aktiven Kriterium) |
| Namen | Beschriftung an den Punkten ein-/ausblenden |
| Zurück | Letzte Eingabe rückgängig (auch Cmd/Strg + Z) |
| Auswertung | Rangfolge nach Dringlichkeit, als Text kopierbar |
| Neu | Alle Eingaben löschen |

Tasten `1`–`9` wählen direkt ein Kriterium.

## Die vier Felder

Die Achsen teilen das Bild in vier Bereiche. Die Farbe eines Punktes ergibt sich
automatisch daraus, wo er liegt:

| Feld | Bedeutung |
|---|---|
| **Hier ansetzen** (rot) | wichtig, lief aber nicht gut — der eigentliche Handlungsbedarf |
| **Stärke sichern** (grün) | wichtig und lief gut — bewahren |
| **Nebenschauplatz** (gelb) | lief gut, ist aber wenig relevant — hier steckt womöglich zu viel Aufwand |
| **Geringe Priorität** (grau) | wenig wichtig, lief nicht gut — kann warten |

Streuen die Einzelstimmen eines Kriteriums stark, erscheint ein Ring um den Punkt:
das Team ist sich dort uneinig. Die Auswertung vermerkt das als „Team uneinig".

## Kriterien

Dienstplan · Angebote · Ausflüge · Informationsfluss · Zusammenarbeit im Team ·
Zusammenarbeit Team/Leitung · Tagesverantwortlich · Externe Unterstützung · Raummanagement

Zum Ändern die Liste `CRITERIA` am Anfang des `<script>`-Blocks in `index.html` anpassen.

## Daten

Die Eingaben liegen ausschließlich lokal im Browser (localStorage) — ein
versehentlicher Reload verliert nichts. Es werden keine Daten übertragen.
Zum Sichern nach der Sitzung: Auswertung → „Als Text kopieren".
