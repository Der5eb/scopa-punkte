---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

# Surface: Scopa Punktezähler (index.html)

Scope: die ganze App (Setup, Spiel, Rundeneingabe, Primiera-Rechner, Verlauf, Spielende). Mode: Operate.

Audience/Job: 2 Spieler oder 2 Teams am Tisch; nach jeder Hand die Runde in Sekunden eintragen, Spielstand aus einem Meter lesen. Constraints: eine statische Datei, offline, localStorage `scopa_v1` kompatibel, Primiera immer über Karten-Rechner.

Chosen direction: der Kategorie-Standard (vom Nutzer gewählt), auf dem Niveau von Keeping Score / ScoreKeeper XL und den iOS-Systemapps. Memorable moment: nach dem Speichern zählen die Punkte hoch und ein „+n“ steigt aus jeder Kachel.

## Direction contract

THESIS: Ein Punktezähler, der sich wie eine iOS-Systemapp anfühlt: gruppierte Listen, Segmented Controls, Stepper, große Zahlen. Er verweigert die lange Formularseite mit Icon-Tabelle und Modal-Popups.

OWN-WORLD: systemGroupedBackground-Grau (#F2F2F7) bzw. Schwarz im Dark Mode, weiße/#1C1C1E-Inset-Gruppen mit 12px Radius, Systemschrift mit Tabellenziffern, ein Akzent Spieltisch-Grün (#1F7A4D) für Primäraktion, Auswahl und Führung; die vier Kartenfarben nur im Primiera-Rechner.

STORY: Wer führt und wie weit es noch ist, steht oben. Darunter die laufende Runde in der Reihenfolge des Auszählens. Speichern zeigt vorher die Punkte der Runde, Fehler nimmt ein Rückgängig-Toast zurück.

FIRST VIEWPORT: Kopfzeile „Scopa“ mit Runde und Ziel, Menü-Knopf rechts. Spieler-Kacheln im 2er-Raster mit 56px-Punktzahl, „noch n“ und Fortschrittsbalken, Führender mit grünem Ring. Darunter Gruppe „Runde n“ beginnend mit Scope-Steppern. Fixe untere Leiste mit Vorschau „+4 · +1“ und grünem Knopf „Runde speichern“.

FORM: Kategorie-Standard (canon), aus der sicheren Neuwürfel-Runde gewählt. seed:8da39430f5420e84

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

Unresolved: keine.
