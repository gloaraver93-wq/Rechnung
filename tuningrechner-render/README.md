# Tuningrechner – Rechnung (für Render)

Reine Website aus einer Datei (`index.html`). Kein Server, keine Datenbank, kein Passwort. Render hostet sie als „Static Site“ (kostenlos möglich).

## Schritt für Schritt
1. **GitHub:** Neues Repository anlegen (github.com → „New repository“). Auf der Repository-Seite „Add file → Upload files“. Die Dateien aus dem ZIP **entpackt** hochladen (`index.html`, `render.yaml`, `README.md`), sodass sie ganz oben im Repository liegen, nicht in einem Unterordner. „Commit changes“ klicken.
2. **Render:** Auf render.com anmelden und mit GitHub verbinden.
3. **Variante A (am einfachsten):** „New → Static Site“, dein Repository wählen.
   - Build Command: leer lassen
   - Publish Directory: `.`
   - „Create Static Site“
4. **Variante B:** „New → Blueprint“, Repository wählen, `render.yaml` wird gelesen, „Apply“.
5. Nach dem Deploy erhältst du eine Adresse wie `https://tuningrechner-rechnung.onrender.com`. Diesen Link kannst du weitergeben.

## Eigene Domain (optional)
Render → dein Dienst → Settings → Custom Domains → Domain eintragen und die DNS-Einträge beim Domain-Anbieter setzen. HTTPS richtet Render automatisch ein.

## Änderungen später
Neue `index.html` im GitHub-Repository hochladen („Add file → Upload files“, gleiche Datei überschreiben). Render veröffentlicht automatisch neu.

## Hinweis zu den Daten
Teile und Rechnungen werden im Browser des jeweiligen Besuchers gespeichert, nicht auf Render. Über „🗄️ Sicherung“ in der Seite lassen sich Daten sichern und auf ein anderes Gerät übertragen.
