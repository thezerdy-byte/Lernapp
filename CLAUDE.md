# Lernapps: Grundregeln für alle Apps

Statische Lern-Apps für eine Mittelschule in Bayern (LehrplanPLUS), veröffentlicht über GitHub Pages (Repo `thezerdy-byte/Lernapp`, Branch `main`). Eine App = ein Ordner `fach/app-name/index.html`, eine einzelne HTML-Datei ohne externe Abhängigkeiten, auf Deutsch, handy- und tablettauglich.

## Kompetenzniveaus (gilt für jede neue App)

Jede Aufgabe gehört genau einem von **drei Kompetenzniveaus** (Anforderungsbereichen) an:

1. **Reproduktion**: Gelerntes wiedergeben, benennen, anwenden.
2. **Reorganisation**: Gelerntes ordnen, verknüpfen, erklären, in andere Form übertragen.
3. **Transfer**: Gelerntes auf neue, unbekannte Situationen anwenden, begründen, beurteilen.

- **Jeder Schüler bekommt in jeder App immer alle drei Kompetenzniveaus**, unabhängig von der Differenzierungsstufe. Die Niveaus sind also kein Mittel zur Differenzierung und werden nicht je nach Stufe weggelassen. Eine App enthält Aufgaben aller drei Niveaus in sinnvoller Folge (z. B. von Reproduktion bis Transfer aufbauend).
- Die Datenstruktur der Aufgaben trägt das Niveau (`niveau: 1|2|3`) und die Hilfen je Differenzierungsstufe. Das Niveau wird den Schülern nicht als Etikett angezeigt, wenn es nicht ausdrücklich gewünscht ist.

## Differenzierung (gilt für jede neue App)

- Die Differenzierung erfolgt **innerhalb** jedes der drei Kompetenzniveaus: Zu jeder Aufgabe gibt es drei Fassungen mit unterschiedlichen **Hilfestellungen** je nach Kompetenzstand der Schüler. Qualitativ heißt: nicht nur größere Zahlen oder mehr Aufgaben, sondern andere Unterstützung (z. B. Stufe 1 mit Hinweis, Beispiel, Zwischenschritten und Antwortauswahl, Stufe 2 mit knappem Tipp, Stufe 3 offen und ohne Hilfe).
- Die Differenzierung ist für die Schüler **nicht erkennbar**: keine Beschriftungen wie „leicht/mittel/schwer", „Stufe 1–3", Sterne, Farben oder Symbole, die ein Niveau verraten. Alle sehen dieselbe Oberfläche und dasselbe Ziel; nur Aufgabenstellung und Hilfen unterscheiden sich unauffällig.
- Zuteilung der Stufe, standardmäßig:
  1. Die App beginnt mit Stufe 2 und passt die Stufe still an das Antwortverhalten an (z. B. nach mehreren Fehlern in Folge eine Stufe tiefer, nach mehreren sicheren richtigen Antworten eine höher).
  2. Die Lehrkraft kann die Startstufe über einen Link-Parameter festlegen (`?stufe=1`, `?stufe=2`, `?stufe=3`). Der Parameter wird nirgends angezeigt.
- Die Punktzahl und Rückmeldungen müssen für alle Stufen fair und gleich wertig wirken. Keine Vergleiche zwischen Schülern anzeigen.
- Aufgaben und Hilfen trennt man vom Code (Datenstruktur am Anfang der Datei), damit die Lehrkraft sie später leicht ändern kann.

## Weitere Regeln

- Fachinhalte immer von der Lehrkraft prüfen lassen und darauf hinweisen.
- Keine personenbezogenen Daten erfassen. Ergebnisse höchstens lokal im Browser speichern.
- Arbeitsmaterial der Lehrkraft (Arbeitsaufträge, Lösungen, Vorlagen) liegt in `Medien/`. Ist es fertig bearbeitet, wird es nach `Fertig/` verschoben. Beide Ordner stehen in `.gitignore` und werden nie veröffentlicht (Lösungen sind „nur für die Lehrkraft“). Was eine App braucht, wird gezielt ins Repository übernommen. Nur das, was eine App braucht, wird ins Repository übernommen. Dateinamen ohne Leerzeichen und Umlaute. Nichts Urheberrechtlich Geschütztes oder Kinderfotos veröffentlichen.
- Design der Übersichtsseite: `index.html` im Hauptordner (Pastellfarben, umrandete Karten, runde Schaltflächen, Schrift Century Gothic bzw. lokal Questrial aus `fonts/`). Neue Apps nutzen denselben Stil.
- Committen nur die eigenen Ordner plus `index.html`. Pushen nur auf ausdrückliche Anweisung der Lehrkraft.

## Ausnahmen

- `mathe/kopfrechnen` und `mathe/kopfrechenfussball` bleiben bewusst so, wie sie sind (offene Stufenwahl, altes Design). Auf ausdrückliche Anweisung der Lehrkraft nicht ändern. Die Regeln oben gelten nur für neue Apps.
