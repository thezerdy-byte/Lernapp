# Lernapps: Grundregeln für alle Apps

Statische Lern-Apps für eine Mittelschule in Bayern (LehrplanPLUS), veröffentlicht über GitHub Pages (Repo `thezerdy-byte/Lernapp`, Branch `main`). Eine App = ein Ordner `fach/app-name/index.html`, eine einzelne HTML-Datei ohne externe Abhängigkeiten, auf Deutsch, handy- und tablettauglich.

## Differenzierung (gilt für jede neue App)

- Jede App differenziert die Aufgaben qualitativ in **drei Niveaustufen** nach Kompetenzniveau. Qualitativ heißt: nicht nur größere Zahlen oder mehr Aufgaben, sondern unterschiedliche **Hilfestellungen** (z. B. Stufe 1 mit Hinweis, Beispiel oder Zwischenschritten und Antwortauswahl, Stufe 2 mit knappem Tipp, Stufe 3 offen und ohne Hilfe, mit Transferaufgaben).
- Die Differenzierung ist für die Schüler **nicht erkennbar**: keine Beschriftungen wie „leicht/mittel/schwer", „Stufe 1–3", Sterne, Farben oder Symbole, die ein Niveau verraten. Alle sehen dieselbe Oberfläche und dasselbe Ziel; nur Aufgabenstellung und Hilfen unterscheiden sich unauffällig.
- Zuteilung der Stufe, standardmäßig:
  1. Die App beginnt mit Stufe 2 und passt die Stufe still an das Antwortverhalten an (z. B. nach mehreren Fehlern in Folge eine Stufe tiefer, nach mehreren sicheren richtigen Antworten eine höher).
  2. Die Lehrkraft kann die Startstufe über einen Link-Parameter festlegen (`?stufe=1`, `?stufe=2`, `?stufe=3`). Der Parameter wird nirgends angezeigt.
- Die Punktzahl und Rückmeldungen müssen für alle Stufen fair und gleich wertig wirken. Keine Vergleiche zwischen Schülern anzeigen.
- Aufgaben und Hilfen trennt man vom Code (Datenstruktur am Anfang der Datei), damit die Lehrkraft sie später leicht ändern kann.

## Weitere Regeln

- Fachinhalte immer von der Lehrkraft prüfen lassen und darauf hinweisen.
- Keine personenbezogenen Daten erfassen. Ergebnisse höchstens lokal im Browser speichern.
- Medien liegen in `Medien/` (Vorlagen, nicht automatisch veröffentlicht). Nur das, was eine App braucht, wird ins Repository übernommen. Dateinamen ohne Leerzeichen und Umlaute. Nichts Urheberrechtlich Geschütztes oder Kinderfotos veröffentlichen.
- Design der Übersichtsseite: `index.html` im Hauptordner (Pastellfarben, umrandete Karten, runde Schaltflächen, Schrift Century Gothic bzw. lokal Questrial aus `fonts/`). Neue Apps nutzen denselben Stil.
- Committen nur die eigenen Ordner plus `index.html`. Pushen nur auf ausdrückliche Anweisung der Lehrkraft.

## Ausnahmen

- `mathe/kopfrechnen` und `mathe/kopfrechenfussball` bleiben bewusst so, wie sie sind (offene Stufenwahl, altes Design). Auf ausdrückliche Anweisung der Lehrkraft nicht ändern. Die Regeln oben gelten nur für neue Apps.
