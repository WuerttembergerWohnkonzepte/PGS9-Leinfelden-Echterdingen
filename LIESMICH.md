# Paul-Gerhardt-Straße 9, Leinfelden-Echterdingen, Wohnung Nr. 2

## Was in diesem Ordner liegt

    index.html          das Exposé
    bilder/             23 Bilddateien, vom Exposé eingebunden
    unterlagen/         20 PDF, über die Downloadkarten verlinkt

Alle drei müssen beieinander bleiben. Fehlt "bilder", zeigt die Seite keine
Fotos. Fehlt "unterlagen", gehen die Downloads ins Leere.

## Hochladen

Ein eigenes Repository für diese Wohnung anlegen. Dann auf "Add file", danach
"Upload files", und in das Fenster alles drei zusammen ziehen:

    index.html
    bilder            (der ganze Ordner)
    unterlagen        (der ganze Ordner)

Wichtig: nicht den Ordner "Wohnung-Leinfelden" hochladen, sondern seinen
Inhalt. Die index.html muss im Repository ganz oben liegen.

## Pages einschalten

Settings, dann Pages. Bei Source "Deploy from a branch" wählen, Branch `main`,
Ordner `/ (root)`. Speichern. Der erste Aufbau dauert ein bis zwei Minuten.

## Danach: Link im Exposé eintragen

In der index.html steht im Finanzierungsabschnitt eine Zeile, die noch leer ist:

    var EXPOSE_URL = "";

Dort die Adresse der veröffentlichten Seite eintragen, zum Beispiel

    var EXPOSE_URL = "https://wuerttembergerwohnkonzepte.github.io/PGS9-Wohnung_2/";

Solange das Feld leer ist, steht im Text der Finanzierungs-E-Mail ein
Platzhalter. Alles andere funktioniert auch ohne diesen Eintrag.

## Größen

Keine Datei ist größer als rund 2,6 MB. Der Weblader von GitHub nimmt einzelne
Dateien bis 25 MB. Die Seite lädt beim Besucher mit rund 1,2 MB Text und Bildern
oberhalb der Falz, der Rest wird beim Scrollen nachgeladen. Die 20 PDF liegen
zusammen bei 13,5 MB und werden nur auf Klick geladen.

## Personenbezogene Daten

Alle 20 PDF sind geschwärzt. Entfernt sind Namen und Geburtsdaten der
Eigentümer, Kontonummern der Gemeinschaftskonten, Buchungs- und Aktenzeichen,
die teilmaskierte IBAN und die Kontaktdaten einzelner Sachbearbeiter. Die
Schwärzung entfernt den Inhalt und deckt ihn nicht nur ab: der Text ist auch
nicht mehr kopierbar oder per OCR lesbar. Geprüft wurde jede Seite doppelt,
über Textextraktion und über erneutes OCR.

Sachlich ist nichts gekürzt. Alle Beträge, Beschlüsse, Flächen und Fristen
stehen unverändert in den Dokumenten.

Nicht enthalten, mit Absicht: das Restnutzungsdauergutachten und der
Mietvertrag. Im Exposé steht, dass beide bei ernsthaftem Kaufinteresse
nachgereicht werden. Auf GitHub Pages ist jede Datei im Repository öffentlich
abrufbar, auch wenn sie auf der Seite nicht verlinkt ist. Deshalb bitte nichts
Zusätzliches in den Ordner legen, ohne es vorher zu schwärzen.

## Falls ein Ordner anders heißen soll

In der index.html steht im Skript genau eine Zeile:

    var DOKBASE='unterlagen/';

Nur diese ändern. Der Schrägstrich am Ende muss bleiben. Der Bildordner ist in
den Bildpfaden hinterlegt und heißt "bilder".

## Was noch aktualisiert werden muss

1. **Mietvertrag.** Das Exposé sagt an vier Stellen ausdrücklich, dass noch kein
   Mietvertrag vorliegt und alle Mietangaben Zielmieten sind: im Hero, in
   Kapitel 03, im Rechner und in den rechtlichen Hinweisen. Sobald der Vertrag
   unterschrieben ist, müssen diese vier Stellen geändert werden.
2. **Fotos des fertigen Zustands.** Die sieben Visualisierungen im Abschnitt
   "So sieht die Wohnung nach der Sanierung aus" sind als Visualisierungen
   gekennzeichnet. Nach der Fertigstellung durch echte Aufnahmen ersetzen und
   den Hinweistext darunter anpassen.
3. **Bild vom Bad.** `bilder/06_vis_bad.jpg` hat nur 445 × 594 Pixel und fällt
   gegenüber den anderen ab. Ersetzen, sobald eine größere Fassung vorliegt.
4. **Bodenrichtwert.** Der Gebäudeanteil von 76,8 Prozent ist im Exposé als
   Annahmewert gekennzeichnet. Er unterstellt bei 470 m² Grundstück und
   285/1.000 Miteigentumsanteilen einen Bodenrichtwert von rund 533 € je m².
   Der tatsächliche Wert steht in BORIS-BW.
5. **Vertrauenszahlen.** 101 Google-Bewertungen im Band unter dem Hero. Bei
   Bedarf aktualisieren.

## Hinweis zum Öffnen von der Festplatte

Öffnest du die index.html per Doppelklick, sperrt der Browser bei manchen
Einstellungen den Zugriff auf Nachbarordner. Die Seite erscheint, das
Sammelpaket als ZIP funktioniert dort aber nicht. Die einzelnen Downloads und
alles Weitere gehen. Auf der veröffentlichten Seite funktioniert alles.
