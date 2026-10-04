# Glossa – Latein Zeile für Zeile übersetzen

Glossa ist eine kleine Website zum Üben von Lateinübersetzungen. Du fügst einen lateinischen
Originaltext ein, übersetzt ihn Zeile für Zeile ins Deutsche und exportierst das Ergebnis
interlinear: eine Zeile Latein, darunter die deutsche Übersetzung in Grün, dann die nächste Zeile.

Alles steckt in einer einzigen Datei (`index.html`). Es gibt keinen Server und keine Installation.

## Starten

- **Lokal:** `index.html` herunterladen und im Browser öffnen.
- **Online über GitHub Pages:** Im Repository unter *Settings → Pages* als Quelle den Branch
  wählen, auf dem `index.html` liegt (Ordner `/ (root)`). Danach ist Glossa unter
  `https://<benutzername>.github.io/latein/` erreichbar.

## So funktioniert es

1. **Text:** Titel, Autor/Stelle und den lateinischen Text einfügen. Wähle, wie aufgeteilt wird:
   - *Zeilen wie eingefügt* – für Gedichte und Verse
   - *Sätze* – teilt nach `.` `!` `?` (abgekürzte Vornamen wie „M. Tullius“ bleiben zusammen)
   - *Sinnabschnitte* – teilt zusätzlich nach `;` und `:`

   Zeilen- und Kapitelnummern („5“, „[2]“) und Silbentrennungen aus kopierten Textausgaben
   werden auf Wunsch entfernt. Eine Vorschau zeigt sofort, welche Zeilen entstehen.
2. **Übersetzen:** Unter jeder lateinischen Zeile steht eine Linie für die Übersetzung.
   - `Enter` springt zur nächsten Zeile, `Shift + Enter` macht einen Zeilenumbruch
   - `Alt + ↑/↓` wechselt die Zeile, `Alt + U` markiert sie als unsicher, `Alt + N` öffnet eine Notiz
   - Ein Klick auf ein lateinisches Wort öffnet Navigium, PONS, Wiktionary oder eine Formanalyse,
     speichert das Wort als Vokabel oder teilt die Zeile vor diesem Wort. Bei Wörtern auf *-que*
     schlägt Glossa auch das Wort ohne *-que* vor.
   - Über `⋯` lassen sich Zeilen verbinden, bearbeiten, einfügen oder löschen (mit Rückgängig).
   - Seitenleiste: Fortschritt, Vokabelliste und ein Spickzettel zu AcI, NcI, Ablativus absolutus,
     PC, Gerundium/Gerundivum, *cum/ut/ne* und häufigen kleinen Wörtern.
3. **Export:** Die Vorschau zeigt genau, was exportiert wird.
   - *Formatiert kopieren* und in Word, Pages oder Google Docs einfügen – Farben bleiben erhalten
   - Herunterladen als Word (`.docx`), HTML oder Text, oder Drucken bzw. als PDF speichern
   - Einstellbar: Titel, Notizen, (?) bei unsicheren Zeilen, Vokabelliste, Zeilenzählung
     (keine, jede, alle 5 Zeilen wie in Textausgaben), leere Schreiblinie für noch offene Zeilen,
     Grünton, Schrift und Schriftgröße

## Speichern

Glossa speichert automatisch im Browser (`localStorage`). Die Daten bleiben auf deinem Gerät und
in diesem Browser. Mit *Projekt sichern* lädst du ein Projekt als `.json`-Datei herunter und kannst
es mit *Projekt laden* auf einem anderen Gerät wieder öffnen.

## Beispieltexte

Zum Ausprobieren sind drei gemeinfreie Texte eingebaut: Caesar, *De bello Gallico* 1,1;
Cicero, *In Catilinam* 1,1; Catull, *Carmen* 5.
