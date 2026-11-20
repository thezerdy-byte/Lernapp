# Anleitung: Gruppenpuzzle „Der Sturm bricht los – 1789“ (GPG 7aM)

Gleiche Technik und Optik wie das Gruppenpuzzle „Vor der Französischen Revolution“. Gedacht für die Erarbeitung der Stunde (Artikulation vom 24.11.2026): Einzelarbeit 5 Min., Expertengruppe 4 Min., Stammgruppe 9 Min.

> **Bitte prüfen:** Texte, Aufgaben und Lösungen stehen im Objekt `CONTENT` am Anfang des Skripts in `index.html`. Die Texte sind frei nacherzählt nach dem Schulbuch S. 54/55 und an einigen Stellen ergänzt (z. B. Soldaten um Paris, Brotpreis, Waffen in der Bastille).

## Themen (Expertengruppen)
- **A Eine Versammlung in Versailles** (5. Mai 1789), erzählt von Pierre. Statt Markieren: Grafik „Abstimmung nach Ständen / nach Köpfen“ mit Beispiel und Fragen, danach richtige Aussagen auswählen
- **B Der Ballhausschwur** (17./20. Juni 1789), erzählt von Pierre
- **C Der Sturm auf die Bastille** (14. Juli 1789), erzählt von Anne
- **D Die Revolution auf dem Land** (Juli/August 1789), erzählt von Jacques

Die Artikulation sieht drei Expertengruppen (A–C) vor. Wenn du D nicht nutzt, teile einfach keine D-Rolle zu.

## Klassenliste mit Nummern (automatische Zuteilung)
Im `CONTENT`-Block von `index.html` gibt es das Feld `klassenliste`. Pro Kind eine Zeile: **Nummer aus deiner Klassenliste, Thema, Symbol, Startstufe** (die Startstufe darf fehlen, dann gilt 2), zum Beispiel:

```
klassenliste: `
  1 A ● 1
  2 B ■ 3
  3 C ▲
  4 D ● 2
`,
```

- **Startstufe:** 1 = viel Hilfe (Antippen, Wortspeicher), 2 = Satzanfänge, 3 = ohne Hilfen. Danach passt sich die Hilfe wie gewohnt still an: Wer gut und schnell arbeitet, bekommt schwerere Aufgaben, bei Fehlern oder langer Zeit mehr Hilfe.

- Statt ● ■ ▲ gehen auch die Wörter Kreis, Quadrat, Dreieck.
- Steht etwas in der Liste, geben die Kinder ihren Vornamen und ihre **Nummer** ein. Die App zeigt dann ihr Thema und Symbol an. Unbekannte Nummern werden abgelehnt („Frag deine Lehrkraft“). Mit „Ich weiß meine Nummer nicht“ geht es auch von Hand.
- Ist die Liste leer, wählen die Kinder Symbol und Thema selbst wie bisher.
- **Keine Namen in die Liste schreiben:** Die Seite ist öffentlich.

## So hängen die Themen zusammen
- Jedes Thema beginnt mit „Was bisher geschah“.
- In der Expertengruppe vermuten die Kinder, wie es weitergeht. Die nächste Person in der Stammgruppe bestätigt oder widerlegt die Vermutung.
- In der Stammgruppe wird **A → B → C → D** berichtet. Gemeinsam ordnen die Kinder die Ereignisse auf einem Zeitstrahl, wählen zu jedem Ereignis die Folge aus und schreiben ein freies Fazit (zwei bis drei Sätze) mit Wortspeicher. Auf der Übersicht erscheint ein Zeitstrahl mit kleinen Bildern.

## Ablauf in der App
1. **Einzelarbeit:** Text lesen und Wichtiges markieren, Stichworte notieren (Wann? Wo? Wer? Was?).
2. **Finde deine Expertengruppe:** Groß steht „Versailles“, „Ballhaus“, „Bastille“ oder „Land“. Weiter mit „Wir haben uns gefunden“.
3. **Expertengruppe:** Ergebnisse vergleichen, drei Kernpunkte festlegen, Vermutung, Zusatzfrage für Schnelle.
4. **Finde deine Stammgruppe:** Groß erscheint das Symbol ● ■ ▲.
5. **Stammgruppe:** Zeitstrahl, Folgen, Fazit.
6. **Fertig:** Übersicht und Ausdruck auf einer Seite.

- **Einzelarbeit:** Die Aufgaben erscheinen nacheinander. Aufgabe 2 kommt erst, wenn Aufgabe 1 geschafft ist und das Kind auf „Weiter zu Aufgabe 2“ tippt.
- **Differenzierung (nur Einzelarbeit):** Alle starten mit Stufe 2 (Satzanfänge, Anzahl-Hinweise). Vor jeder neuen Aufgabe passt die App die Hilfe still an:
  - 2 oder mehr Fehlversuche **oder** länger als 2 Minuten → eine Stufe mehr Hilfe (Stufe 1: Antippen, Wortspeicher, sofortige Rückmeldung)
  - keine Fehler **und** schneller als 45 Sekunden → eine Stufe weniger Hilfe (Stufe 3: leere Felder, keine Hinweise)
  - Die Startstufe kann per Link festgelegt werden: `…/gruppenpuzzle-1789/?stufe=1` (oder 2, 3).
  - Die Werte stehen in `CONTENT.anpassung`.
- **Symbol ● ■ ▲:** dient nur noch zum Finden der Stammgruppe.
- Expertengruppe, Stammgruppe und Übersicht sehen für alle gleich aus.
- **Leitfiguren:** Pierre, Anne und Jacques erscheinen mit Bild oben in der Einzelarbeit.
- **Stiller Timer:** keine sichtbare Uhr. Die nächste Phase öffnet sich, wenn alles erledigt ist, oder nach 40 % der geplanten Zeit (Zeiten in `CONTENT.minuten`).

## Bilder
- Eröffnung der Generalstände 1789, Stich nach Jean-Michel Moreau (gemeinfrei)
- Der Schwur im Ballhaus, nach Jacques-Louis David (gemeinfrei)
- Die Sieger der Bastille, Paul Delaroche (gemeinfrei)
- Aufständische Bauern, Louis-Charles Bombled (gemeinfrei)

QR-Code: mit `../gruppenpuzzle-franzoesische-revolution/qr.html` erzeugen.
