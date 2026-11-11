# Tuningrechner – Rechnung

Eine einzelne Website-Datei (`index.html`) ohne Server, ohne Login, ohne Datenbank. Jeder, der den Link öffnet, kann Rechnungen erstellen.

## Funktionen
- Rechnung mit Nummer, Datum, Zahlungsziel, Status (Offen, Bezahlt, Storniert), Kunde und Absender
- Teile antippen oder eigene Positionen eintragen; Mengen und Preise direkt änderbar
- Rabatt in %, MwSt in %, Zwischensumme, Netto, Gesamtbetrag
- Einzelpreise und Zwischensummen auf der Rechnung ein- oder ausblendbar
- Live-Vorschau der Rechnung, Drucken oder als PDF speichern, Text kopieren
- Verlauf: Rechnungen speichern, öffnen, duplizieren, Status ändern, löschen
- Teile verwalten: hinzufügen, ändern, löschen, Emoji oder eigenes PNG (Transparenz bleibt erhalten)
- Sicherung: alle Daten als Text oder Datei sichern und wiederherstellen

## Wo liegen die Daten?
Nur im Browser des jeweiligen Besuchers (kein gemeinsamer Server). Jeder Besucher hat seine eigene Teileliste und seine eigenen Rechnungen. Wer Daten auf ein anderes Gerät mitnehmen will, nutzt „🗄️ Sicherung“.

## Online stellen
Die Datei `index.html` bei einem Hoster für statische Seiten hochladen, zum Beispiel Cloudflare Pages, Netlify oder GitHub Pages. Es ist kein Build-Befehl nötig. Danach hast du eine Adresse, die du weitergeben kannst.

## PDF erstellen
„🖨️ Drucken / PDF“ → im Druckfenster als Ziel „Als PDF speichern“ wählen. Nur die Rechnung wird gedruckt, nicht die Bedienelemente.
