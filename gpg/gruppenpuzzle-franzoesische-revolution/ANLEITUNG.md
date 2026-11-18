# Anleitung: Gruppenpuzzle „Vor der Französischen Revolution“ (GPG 7aM)

Die App besteht aus **einer Datei** (`index.html`). Sie braucht kein Netz nach dem ersten Laden, keinen Login und erfasst nur den Vornamen, und der bleibt auf dem jeweiligen iPad.

> **Bitte prüfen:** Aufgaben, Lösungen, Wortspeicher und Quizfragen stehen im Objekt `CONTENT` am Anfang des Skripts in `index.html`. Die Inhalte sind nach deinem Auftrag erstellt, aber noch nicht gegen das Schulbuch (S. 48–51) abgeglichen.

## So kommt die App auf die iPads

### Weg 1: Netlify Drop (einfachster Weg)
1. Öffne **app.netlify.com/drop** im Browser (am Computer).
2. Lege einen neuen Ordner an (z. B. `gruppenpuzzle`) und kopiere **`index.html`** und **`qr.html`** hinein.
3. Ziehe den **Ordner** auf die Seite. Netlify erzeugt sofort einen Link, z. B. `https://irgendein-name.netlify.app`.
4. Der Link zur App ist dieser Link. Er zeigt `index.html`.
5. Ohne Konto ist die Seite nur kurze Zeit online. Mit kostenlosem Konto bleibt sie bestehen.

### Weg 2: GitHub Pages
Liegt der Ordner im Repository `thezerdy-byte/Lernapp` auf dem Branch `main` und ist gepusht, erreichst du die App unter  
`https://thezerdy-byte.github.io/Lernapp/gpg/gruppenpuzzle-franzoesische-revolution/`  
(die genaue Adresse bitte einmal im Browser prüfen). Nach dem Push dauert es meist 1 bis 2 Minuten.

### QR-Code für die Klasse
1. Öffne **`qr.html`** (direkt per Doppelklick am Computer oder unter dem Link, z. B. `…/qr.html`).
2. Füge den Link der App ein und tippe auf „QR-Code erzeugen“.
3. Zeige den Code am Beamer. Die Schüler scannen ihn mit der Kamera des iPads. Der Generator arbeitet ohne Internet und ohne fremde Bibliothek.

## Einsatz in der Stunde
- Die App wird nur in der **Arbeitsphase** (ca. 40 Minuten) genutzt: Expertenphase (22 Min.), Stammgruppe (18 Min.). Einstieg, Sicherung und Transfer laufen im Plenum.
- **Anmeldung:** Vorname, Symbol, Rolle.
  - Das **Symbol teilst du zu**. Es steuert unauffällig die Hilfen:
    - ● Kreis: Wortspeicher, Lückentext, Zuordnung zum Antippen
    - ■ Quadrat: Textfelder mit Satzanfängen
    - ▲ Dreieck: leere Textfelder
  - In der App steht nirgends, was die Symbole bedeuten.
  - **Rollen:** A Ein Bauer (S. 48), B Eine adlige Dame (S. 50), C Gelehrte Bürger (S. 51), D Revolutionäre (S. 49).
- Die App speichert den Stand automatisch auf dem iPad. Wer die Seite schließt, macht danach weiter. „Neu beginnen“ löscht alles (mit Rückfrage).
- Schritte: 1 Expertenphase (Aufgaben, Experten-Check, Spickzettel) · 2 Stammgruppe (Gruppenblatt, Reihenfolge B → A → C → D) · 3 Fertig (Übersicht, Drucken / PDF).
- **Experten-Check:** Ab 3 von 4 richtigen Antworten erscheint der Spickzettel. Er wird in die eigene Spalte des Gruppenblatts übernommen.

## Drucken
Auf „Fertig“ den Knopf „Drucken / als PDF sichern“ antippen. Es entstehen zwei DIN-A4-Seiten (Expertenaufgaben, Gruppenblatt) mit Vorname und Rolle, ohne Symbol und schwarz-weiß-tauglich. Auf dem iPad: im Druckdialog „PDF sichern“ oder über das Teilen-Menü.

## Inhalte ändern
Alles Fachliche steht in `CONTENT` am Anfang des `<script>` in `index.html` (Aufgaben, Hilfen, Wortspeicher, Check-Fragen, Spickzettel, Gruppenblatt). Eine Erklärung der Felder steht direkt darüber im Kommentar. Nach einer Änderung die Datei erneut hochladen bzw. pushen.

## Hinweise
- Die App enthält **keine** Buchtexte oder Buchbilder, nur Verweise auf die Nummern im Buch.
- Es werden keine Daten an einen Server gesendet und nichts getrackt.
- Getestet im Browser in den Größen 1024 × 768 und 820 × 1180. Bitte einmal auf einem echten iPad in Safari durchspielen, besonders Ausdruck/PDF.
