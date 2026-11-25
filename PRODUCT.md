# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users
Private Scopa-Runden: meistens zu zweit, manchmal zu viert (dann in zwei Teams). Ein Handy liegt am Tisch; nach jeder Hand trägt jemand die Punkte ein, oft während die Karten noch auf dem Tisch liegen. Die App wird als PWA vom Homescreen gestartet.

## Product Purpose
Das Zählen einer Scopa-Partie abnehmen: pro Hand die Punkte für Karten, Denari, Settebello, Primiera und Scope erfassen, den Spielstand zeigen und erkennen, wann die Zielpunktzahl erreicht ist. Erfolg heißt: eine Runde ist in Sekunden eingetragen, ohne Rechnen und ohne Scrollen-Suchen, und jeder am Tisch sieht sofort, wer führt.

## Positioning
Rechnet die Primiera aus den tatsächlich gehaltenen Karten aus (höchste Karte je Farbe antippen), statt dass am Tisch im Kopf addiert wird; kennt die Kartenlogik (jede Zahlenkarte gibt es nur einmal, Figuren dreimal je Farbe).

## Operating Context
- Einsatz am Spieltisch, Handy in der Hand oder flach auf dem Tisch, wechselndes Licht (Küche, Terrasse, Abend).
- Ablauf einer Hand: Scope fallen während des Spiels, danach werden Karten, Denari, Settebello und Primiera ausgezählt.
- Standard-Ziel 11 Punkte; Partien gehen über mehrere Runden.

## Capabilities and Constraints
- Einzelne statische Seite (index.html) mit Manifest und Service Worker, gehostet auf GitHub Pages unter `/scopa-punkte/`. Kein Build-Schritt.
- Muss offline funktionieren (Spieltische ohne Netz).
- Spielstand bleibt im localStorage erhalten (Schlüssel `scopa_v1`, Spielernamen in `scopa_names`); bestehende Spielstände sollen weiter laden.
- 2 bis 4 Teilnehmer; bei vier Personen werden Teams als Teilnehmer eingetragen.
- Primiera wird immer über den Karten-Rechner erfasst (Wunsch des Nutzers); offizielle Regel: Primiera nur mit mindestens einer Karte jeder Farbe.
- Kartenwerte Primiera: 7=21, 6=18, Ass=16, 5=15, 4=14, 3=13, 2=12, Figur=10.

## Brand Commitments
- Name „Scopa“ / „Scopa Punktezähler“ bleibt.
- Das App-Icon (icon.svg, icon-192.png, icon-512.png: cremefarbene Krone auf dunkelgrünem Verlauf) bleibt unverändert.
- Alles andere am Erscheinungsbild darf neu werden.
- Visuelle Haltung (Entscheidung des Nutzers, Nov. 2026): bewusst der Kategorie-Standard, ein sauberer Look wie iOS-Systemapps auf dem Niveau von Keeping Score / ScoreKeeper XL. Kein Rosa.
- Sprache: Deutsch, italienische Spielbegriffe (Scopa, Denari, Settebello, Primiera, Coppe, Spade, Bastoni).

## Evidence on Hand
Keine Screenshots, Statistiken oder Nutzerstimmen vorhanden; nichts davon erfinden.

## Product Principles
1. Eintragen schlägt Anschauen: die häufigste Handlung (eine Runde erfassen) braucht die wenigsten Taps.
2. Der Spielstand ist für alle am Tisch lesbar, auch aus einem Meter Abstand.
3. Die App rechnet, der Mensch tippt nur, was er auf dem Tisch sieht.
4. Fehler sind billig: alles lässt sich ohne Nachfrage-Dialoge zurücknehmen.
5. Funktioniert offline und überlebt das Neuladen.
