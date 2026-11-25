---
name: Scopa Punktezähler
description: Punktezähler für Scopa im Stil einer iOS-Systemapp, gruppierte Listen, große Zahlen, ein grüner Akzent.
colors:
  grouped-bg: "#F2F2F7"
  surface: "#FFFFFF"
  fill: "rgba(118,118,128,.12)"
  fill-press: "rgba(118,118,128,.24)"
  label: "#000000"
  label-secondary: "#5E5E63"
  separator: "rgba(60,60,67,.2)"
  primary: "#1F7A4D"
  primary-press: "#17603C"
  on-primary: "#FFFFFF"
  primary-text: "#1F7A4D"
  primary-soft: "rgba(31,122,77,.12)"
  danger: "#D70015"
  segment-on: "#FFFFFF"
  bar-material: "rgba(249,249,251,.92)"
  toast: "#1C1C1E"
  toast-text: "#FFFFFF"
  toast-action: "#5FD49A"
  suit-denari: "#9A6B00"
  suit-coppe: "#C0392B"
  suit-spade: "#2E6BB0"
  suit-bastoni: "#237A41"
  grouped-bg-dark: "#000000"
  surface-dark: "#1C1C1E"
  fill-dark: "rgba(118,118,128,.24)"
  fill-press-dark: "rgba(118,118,128,.4)"
  label-dark: "#FFFFFF"
  label-secondary-dark: "#AEAEB2"
  separator-dark: "rgba(84,84,88,.65)"
  primary-dark: "#34C77B"
  primary-press-dark: "#2BA866"
  on-primary-dark: "#00230F"
  primary-text-dark: "#4CD58B"
  primary-soft-dark: "rgba(52,199,123,.16)"
  danger-dark: "#FF6961"
  segment-on-dark: "#636366"
  bar-material-dark: "rgba(22,22,24,.9)"
  toast-dark: "#3A3A3C"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "56px"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "-0.03em"
    fontFeature: "tnum"
  display-compact:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "44px"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "-0.03em"
    fontFeature: "tnum"
  large-title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "34px"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "28px"
    fontWeight: 700
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 700
    letterSpacing: "-0.01em"
  count:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 600
    fontFeature: "tnum"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.35
  button:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 600
  callout:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 500
  footnote:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.4
  card-value:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 700
    lineHeight: 1.1
  card-points:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Text\", \"Segoe UI\", Roboto, \"Helvetica Neue\", system-ui, sans-serif"
    fontSize: "11px"
    lineHeight: 1
    fontFeature: "tnum"
rounded:
  segment-thumb: "7px"
  control: "9px"
  group: "12px"
  sheet: "14px"
  tile: "16px"
  pill: "18px"
  full: "50%"
spacing:
  xs: "4px"
  sm: "8px"
  tile-gap: "10px"
  md: "12px"
  inset: "16px"
  section: "28px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.group}"
    padding: "0 20px"
    height: "50px"
  button-primary-active:
    backgroundColor: "{colors.primary-press}"
  button-tinted:
    backgroundColor: "{colors.primary-soft}"
    textColor: "{colors.primary-text}"
    typography: "{typography.button}"
    rounded: "{rounded.group}"
    padding: "0 20px"
    height: "50px"
  button-plain:
    textColor: "{colors.primary-text}"
    typography: "{typography.body}"
    padding: "0 4px"
    height: "44px"
  icon-button:
    backgroundColor: "{colors.fill}"
    textColor: "{colors.primary-text}"
    rounded: "{rounded.full}"
    size: "44px"
  group:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.group}"
  list-row:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.label}"
    typography: "{typography.body}"
    padding: "10px 16px"
    height: "48px"
  row-button-danger:
    textColor: "{colors.danger}"
    typography: "{typography.body}"
    padding: "10px 16px"
  segmented-control:
    backgroundColor: "{colors.fill}"
    rounded: "{rounded.control}"
    padding: "2px"
  segmented-control-selected:
    backgroundColor: "{colors.segment-on}"
    textColor: "{colors.label}"
    typography: "{typography.callout}"
    rounded: "{rounded.segment-thumb}"
    height: "38px"
  stepper:
    backgroundColor: "{colors.fill}"
    textColor: "{colors.label}"
    rounded: "{rounded.control}"
    height: "40px"
    width: "105px"
  score-tile:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.label}"
    typography: "{typography.display}"
    rounded: "{rounded.tile}"
    padding: "14px 16px 16px"
  score-tile-compact:
    typography: "{typography.display-compact}"
    padding: "12px 14px 14px"
  chip:
    backgroundColor: "{colors.surface}"
    typography: "{typography.callout}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: "36px"
  primiera-card:
    backgroundColor: "{colors.fill}"
    typography: "{typography.card-value}"
    rounded: "{rounded.control}"
    height: "50px"
  notice:
    backgroundColor: "{colors.primary-soft}"
    textColor: "{colors.primary-text}"
    typography: "{typography.callout}"
    rounded: "{rounded.group}"
    padding: "12px 16px"
  toast:
    backgroundColor: "{colors.toast}"
    textColor: "{colors.toast-text}"
    rounded: "{rounded.sheet}"
    padding: "10px 10px 10px 18px"
  bottom-sheet:
    backgroundColor: "{colors.grouped-bg}"
    textColor: "{colors.label}"
    rounded: "{rounded.sheet}"
    padding: "8px 16px 20px"
---

# Design System: Scopa Punktezähler

## Overview

**Creative North Star: "Die Systemapp am Spieltisch"**

Der Punktezähler sieht aus und benimmt sich wie eine App, die mit dem iPhone kommt: grauer gruppierter Hintergrund, weiße Inset-Gruppen, Systemschrift, ein einziger Akzent. Das ist eine bewusste Entscheidung des Nutzers für den Kategorie-Standard (Niveau Keeping Score / ScoreKeeper XL), keine Verlegenheit. Die Eigenheit des Produkts liegt nicht in einer eigenen Ästhetik, sondern in großen, aus einem Meter lesbaren Zahlen, im Kartenraster der Primiera und darin, dass jede Eingabe ohne Rückfrage zurücknehmbar ist.

Die Dichte ist die einer iOS-Einstellungsliste: 48px-Zeilen, 16px Einzug, 28px zwischen Abschnitten. Oben steht der Spielstand in Kacheln, darunter folgen die Abschnitte der laufenden Runde in der Reihenfolge des Auszählens, unten hält eine fixe Materialleiste die Vorschau und den Speichern-Knopf. Tiefe entsteht durch Tonwerte und durchscheinendes Material, nicht durch Schatten.

Das Grün (#1F7A4D, im Dark Mode heller) erinnert an den Spieltisch und trägt drei Bedeutungen: Primäraktion, Auswahl, Führung. Die vier Kartenfarben treten ausschließlich im Primiera-Rechner auf. Kein Rosa (Nutzerentscheidung).

**Key Characteristics:**
- Grouped-Inset-Listen auf systemGroupedBackground, Light und Dark Mode vollständig über Custom Properties.
- Systemschrift durchgehend, Zahlen immer mit Tabellenziffern.
- Ein Akzent, Kartenfarben nur im Primiera-Rechner.
- Flach; Tiefe über Tonstufen, Blur-Material und einen einzigen Toast-Schatten.
- Bewegung nur als Rückmeldung auf Zahlen (Hochzählen, „+n“-Aufstieg) und als iOS-Sheet; reduzierte Bewegung schaltet alles ab.
- Deutsche Texte in der „ihr“-Form, italienische Spielbegriffe unübersetzt.

## Colors

Neutrales iOS-Systemgrau mit einem Spieltisch-Grün und vier Kartenfarben, die nur in ihrem eigenen Rechner sprechen.

### Primary
- **Spieltisch-Grün** (`primary`): Füllung des Primärknopfs („Runde speichern“, „Spiel starten“, „Revanche“), Fortschrittsbalken, Ring der führenden Kachel, Fokusring, Textcursor. Im Dark Mode das hellere `primary-dark` mit dunkelgrüner Schrift (`on-primary-dark`).
- **Grün gedrückt** (`primary-press`): Active-Zustand des Primärknopfs.
- **Grün als Text** (`primary-text`): Plain-Buttons, Links, Icon-Button-Glyphen, Krone, „führt · noch n“, „+n“-Delta, Primiera-Gewinner. Im Dark Mode eigenes, helleres `primary-text-dark`, weil Text mehr Kontrast braucht als Flächen.
- **Grüner Hauch** (`primary-soft`): Tinted-Button („Neues Spiel“), Namens-Badge, Hinweisfläche bei Gleichstand, Textauswahl.

### Tertiary
- **Denari-Gold** (`suit-denari`), **Coppe-Rot** (`suit-coppe`), **Spade-Blau** (`suit-spade`), **Bastoni-Grün** (`suit-bastoni`): Farbpunkt im Kopf jeder Farbreihe und Füllung der gewählten Karte (weiße Schrift) im Primiera-Rechner. In beiden Modi identisch.

### Neutral
- **Gruppierter Hintergrund** (`grouped-bg` / `grouped-bg-dark`): Seitenhintergrund, auch Hintergrund des Bottom Sheets; zugleich `theme-color` und Manifest-Farbe.
- **Gruppenfläche** (`surface` / `surface-dark`): Inset-Gruppen, Kacheln, Chips.
- **Systemfüllung** (`fill`, `fill-press`): Spur der Segmented Controls und Stepper, unausgewählte Karten, Icon-Button, Meter-Spur, Press-Zustand von Zeilen.
- **Label** (`label`) und **Sekundärlabel** (`label-secondary`): Haupttext; Untertitel, Fußnoten, Kachel-Untertext, Kartenpunkte, Platzhalter.
- **Trennlinie** (`separator`): 0.5px-Haarlinien zwischen Zeilen und an den Materialleisten.
- **Segment-Daumen** (`segment-on`): ausgewähltes Segment; im Dark Mode Grau #636366 statt Weiß.
- **Leistenmaterial** (`bar-material`): durchscheinender Grund der unteren Speichern-Leiste und der kompakten Kopfleiste.
- **Toast** (`toast`, `toast-text`, `toast-action`): dunkle Kapsel in beiden Modi, Aktion „Rückgängig“ in hellem Grün.
- **Destruktiv** (`danger`): „Neues Spiel mit anderen Spielern“, „Runde n löschen“, Setup-Fehlermeldung.

### Named Rules
**The Ein-Akzent Rule.** Grün ist die einzige Signalfarbe außerhalb des Primiera-Rechners. Es markiert genau drei Dinge: was man als Nächstes tut, was ausgewählt ist, wer führt. Ein zweiter Akzent kommt nicht dazu.

**The Kartenfarben-bleiben-am-Tisch Rule.** Denari, Coppe, Spade und Bastoni erscheinen nur als Farbpunkt und gewählte Karte im Primiera-Rechner, nie als Kachel-, Spieler- oder Statusfarbe.

**The Zwei-Modi Rule.** Jede Farbe wird über eine Custom Property gesetzt, die im Dunkelmodus überschrieben ist: entweder per `prefers-color-scheme: dark` (Einstellung „System“, solange nicht `data-theme="light"` gesetzt ist) oder erzwungen per `:root[data-theme="dark"]`. Die Wahl System / Hell / Dunkel steht als Segmented Control unter „Darstellung“ im Spielmenü und auf dem Setup-Screen, gespeichert in `localStorage` unter `scopa_theme`, und wird schon im `<head>` gesetzt, damit nichts aufblitzt. Keine Farbe wird in Komponenten fest verdrahtet, außer der weißen Schrift auf gewählten Karten.

## Typography

**Display Font:** Systemschrift (`-apple-system`, „SF Pro Text“, mit Segoe UI, Roboto, Helvetica Neue, system-ui)
**Body Font:** dieselbe Systemschrift

**Character:** Eine Familie, nur Größe und Gewicht schaffen Hierarchie. Die Systemschrift ist hier Material der gewählten Welt (iOS-Systemapp), keine Ersatzlösung.

### Hierarchy
- **Display** (700, 56px, 1, −0.03em, Tabellenziffern): Punktzahl der Spielerkachel bei zwei Spielern. Bei 3 oder 4 Teilnehmern **Display compact** (44px), bis 360px Breite 48px.
- **Large Title** (700, 34px, 1.1, −0.02em): „Scopa“ in der Titelzeile, darunter ein 15px-Untertitel in Sekundärlabel („Runde 3 · bis 11“).
- **Headline** (700, 28px, −0.02em): „Name gewinnt“ im Abschlussblock.
- **Title** (700, 20px, −0.01em): Abschnittsköpfe („Scope“, „Ausgezählt“, „Primiera“, „Verlauf“) und Sheet-Titel; rechts daneben optional ein 15px-Aside in Sekundärlabel.
- **Count** (600, 22px, Tabellenziffern, rechtsbündig, min. 2ch): Wert neben einem Stepper.
- **Body** (400, 17px, 1.35): Zeilenbeschriftungen, Eingabefelder, Zeilen-Buttons. Buttons 17px/600.
- **Callout** (500, 15px): Segment-Beschriftungen (ausgewählt 600), Chips, Vorschau in der Leiste, Toast, Verlaufszeilen, Primiera-Ergebnis.
- **Footnote** (400, 13px, 1.4): Erklärtexte unter Gruppen, Kachel-Untertext („noch 7“), Zeilenhinweise, Fehlertext.
- **Kartenwert** (700, 18px) über **Kartenpunkten** (11px, Tabellenziffern) in jeder Primiera-Karte.

### Named Rules
**The Tabellenziffern Rule.** Jede Zahl, die sich ändert oder neben anderen Zahlen steht (Kacheln, Zähler, Vorschau, Verlauf, Kartenpunkte, kompakte Leiste), läuft mit `font-variant-numeric: tabular-nums`, damit nichts springt.

**The Eine-Familie Rule.** Keine zweite Schrift, keine Webfont. Hierarchie entsteht nur aus den Stufen oben.

## Layout

Eine Spalte, maximal 560px breit und zentriert, 16px Seitenrand (12px bis 360px Breite), oben Safe-Area plus 12px, unten Safe-Area plus 120px Platz für die fixe Leiste. Abschnitte stehen 28px auseinander (im Sheet 18px), Abschnittsköpfe haben 4px Einzug und 8px Abstand zur Gruppe, Fußnoten 8px über und 16px seitlich.

**Spielstand:** Raster mit 2 Spalten und 10px Abstand; bei 3 Teilnehmern 3 Spalten; bei 4 Teilnehmern bleibt es 2×2 mit kompakter Kachel (44px-Zahl, 12/14px Innenabstand).

**Auswahlzeilen:** Bei zwei Spielern mit Namen bis 8 Zeichen steht die Beschriftung links und das Segmented Control (70% Breite) rechts in einer Zeile („Karten“, „Denari“). Sonst stapelt die Zeile Beschriftung über Control. Ab 3 Teilnehmern bricht jedes Segmented Control in 2 Spalten um; ein ungerades letztes Segment (etwa „Gleich“) spannt beide Spalten.

**Primiera-Raster:** 8 Karten nebeneinander mit 6px Abstand; bis 360px Breite 4×2 mit 44px hohen Karten.

**Fixe Leisten:** Untere Leiste an der Unterkante mit 10px Innenabstand plus Safe-Area, Inhalt auf 528px begrenzt; Vorschau links, Primärknopf rechts, bis 360px untereinander und zentriert. Die kompakte Punkteleiste erscheint oben, sobald das Kachelraster aus dem Bild gescrollt ist.

### Named Rules
**The Daumen-zuerst Rule.** Die häufigste Handlung (Runde speichern) sitzt immer in der unteren Leiste, nie im Seitenfluss. Interaktive Ziele sind mindestens 36px hoch, Hauptziele 44 bis 50px.

## Elevation & Depth

Flach. Tiefe entsteht durch drei Tonstufen (Hintergrund, Gruppenfläche, Systemfüllung) und durch durchscheinendes Material (`saturate(180%) blur(20px)`) bei den fixierten Leisten, getrennt durch 0.5px-Haarlinien. Schatten gibt es genau an zwei Stellen: am Daumen des Segmented Controls und am Toast. Der grüne Ring der führenden Kachel und das Aufblitzen einer unvollständigen Gruppe sind innere bzw. äußere 2–3px-Ringe, keine Schatten im Sinne von Höhe.

### Shadow Vocabulary
- **Segment-Daumen** (`box-shadow: 0 3px 8px rgba(0,0,0,.12), 0 1px 1px rgba(0,0,0,.04)`; dark `0 3px 8px rgba(0,0,0,.3)`): hebt das gewählte Segment aus der Spur.
- **Toast** (`box-shadow: 0 8px 24px rgba(0,0,0,.18)`): weicher Umgebungsschatten der schwebenden Kapsel.
- **Führungsring** (`box-shadow: inset 0 0 0 2px` Grün): führende Kachel.
- **Fehlt-noch-Blitz** (`box-shadow: 0 0 0 3px` Grün, 0.9s ausblendend): Gruppe, die beim Speichern noch fehlt.

### Named Rules
**The Material-statt-Schatten Rule.** Was über dem Inhalt liegt (Leisten), wird durchscheinend und durch eine Haarlinie abgesetzt, nicht durch einen Schlagschatten.

## Shapes

Weiche iOS-Rundungen in einer festen Treppe: 7px Segment-Daumen, 9px Spur, Stepper und Karte, 12px Gruppen und Buttons, 14px Sheet-Oberkante und Toast, 16px Spielerkacheln, 18px Chips (Pille), Kreis für Icon-Button, Badge und Entfernen-Knopf. Gruppen schneiden ihren Inhalt ab (`overflow: hidden`). Trennlinien sind 0.5px und beginnen 16px eingerückt, wie in iOS-Listen. Der Fortschrittsbalken ist 4px hoch mit 2px Radius. Icons sind Linien-SVGs (24er Raster, 2px Strich, runde Enden), 20px im Regelfall, 16–18px in Chips, Kacheln und Verlauf.

## Components

### Buttons
Ruhig und eindeutig, wie Systemknöpfe.
- **Shape:** 12px Radius, mindestens 50px hoch, 20px seitlich.
- **Primary:** grüne Fläche, weiße (dark: dunkelgrüne) 17px/600-Schrift. Ohne vollständige Runde bleibt er tippbar, steht aber auf 45% Deckkraft (`aria-disabled`); ein Tipp lässt dann die fehlende Gruppe grün aufblitzen und vibriert kurz.
- **Active:** dunkleres Grün und `scale(.98)`; kein Hover-Zustand (Touch-first).
- **Tinted:** grüner Hauch mit grüner Schrift, gleiche Maße; Nebenaktion neben dem Primärknopf im Abschlussblock.
- **Plain:** grüne Schrift ohne Fläche, 44px hoch („Fertig“ im Sheet). **Link:** 15px/500 grün, für Aktionen in einer Ergebniszeile („Leeren“, „Doch werten“).
- **Icon-Button:** 44px Kreis auf Systemfüllung, grüne Glyphe („…“ für das Spielmenü).
- **Focus:** 2px grüner Outline mit 2px Abstand für alle fokussierbaren Elemente.

### Chips
- **Style:** 36px Pille auf Gruppenfläche, 15px/500, grünes Plus-Icon davor.
- **State:** nur Aktion („Zuletzt gespielt“: Namen übernehmen); Active auf Systemfüllung-gedrückt.

### Cards / Containers
- **Gruppe:** Gruppenfläche, 12px Radius, keine Kontur, kein Schatten; Zeilen innen 10px/16px, mindestens 48px hoch, durch eingerückte Haarlinien getrennt.
- **Zeilenvarianten:** Standard (Label links, Wert rechts), gestapelt (Label über Control, 12px vertikal, 10px Abstand), inline (Label links, Control 70% rechts), Zeilen-Button (ganze Zeile, grüne oder rote Schrift, Active auf Systemfüllung).
- **Hinweis:** grüner Hauch, 12px Radius, 12/16px, grüne 15px/500-Schrift („Gleichstand bei 11 Punkten …“).

### Inputs / Fields
- **Namensfeld:** randloses Textfeld in einer Listenzeile, 17px, Platzhalter in Sekundärlabel, links ein 28px-Kreis-Badge mit dem Anfangsbuchstaben auf grünem Hauch, rechts ab drei Feldern ein 36px-Kreis zum Entfernen.
- **Focus:** grüner Cursor, kein Feldrahmen.
- **Error:** 13px rote Zeile unter der Gruppe, als `role="alert"`.

### Segmented Control
Das zentrale Auswahlelement für „wer hat es“.
- Spur auf Systemfüllung, 9px Radius, 2px Innenabstand und Abstand; Segmente 38px hoch, 15px/500, abgeschnitten mit Ellipse.
- **Ausgewählt:** Daumen in `segment-on` mit Schatten, Schrift 600. Übergang 0.18s.
- **Gleich-Segment:** schmaler (Flex 0.7), außer inline.
- **Umbruch:** ab 3 Teilnehmern 2 Spalten, ungerades letztes Segment über die volle Breite.
- **Mit Zusatz:** im Primiera-Spielerwähler steht hinter dem Namen eine 13px-Zahl (Summe oder „2/4“).
- Technisch native Radios mit Labels; Fokus als 2px-Ring am Segment.

### Stepper
- Zwei 52×40px Felder (bis 360px: 46px) auf Systemfüllung, 9px Radius, dazwischen 1×20px Trennlinie; Plus/Minus als Linien-Icons.
- Der Wert steht links daneben in **Count** (22px/600). Minus ist bei 0 deaktiviert (45%).

### Spielerkachel
Die Signatur: aus einem Meter lesbar.
- Gruppenfläche, 16px Radius, 14/16/16px Innenabstand. Name 15px/600 mit Ellipse, darunter die Punktzahl in Display, Untertext in Footnote („noch 7“, „führt · noch 3“, „gewinnt die Partie“, „4 zurück“), dann ein 4px-Fortschrittsbalken bis zum Ziel.
- **Führend:** 2px grüner Innenring, Krone vor dem Namen, Untertext grün 500. Nur bei eindeutiger Führung.
- **Nach dem Speichern:** Zahl zählt in 520ms (exponentielles Ausrollen) hoch und pulst auf 1.08; oben rechts steigt ein grünes „+n“ auf und blendet in 1.6s aus. Balken wächst in 0.5s.
- **n3 / n4:** 44px-Zahl; n4 zusätzlich engere Polster.

### Kompakte Punkteleiste
- Fixiert oben, Leistenmaterial mit Blur und Haarlinie unten, gleitet in 0.25s herein, sobald die Kacheln aus dem Bild sind. Zentrierte, umbrechende Paare „Name **11**“ in 15px/500, Zahl 700, Führender grün.

### Primiera-Rechner
- Oben ein Segmented Control für den Spieler, darunter vier Farbreihen: Kopf mit 10px-Farbpunkt, Farbname 15px/600 und Punktwert rechts (Sekundärlabel, gesetzt 600 in Label).
- Acht Karten (7, 6, A, 5, 4, 3, 2, F) als 50px hohe Felder auf Systemfüllung, 9px Radius, Wert über Punktzahl. **Gewählt:** Kartenfarbe als Fläche, weiße Schrift. **Vergeben** (bei einem anderen Spieler): 35% Deckkraft, Wert durchgestrichen. Active `scale(.94)`.
- Darunter eine Ergebniszeile mit Haarlinie oben: Sekundärlabel, bei Gewinner Label mit grünem Namen; rechts ein Link als Ausweg.

### Untere Speichern-Leiste
- Fixiert unten, Leistenmaterial mit Blur und Haarlinie oben. Links die Vorschau in 15px: entweder „Noch offen: Settebello, Primiera“ in Sekundärlabel oder „Lena **+4** Tom **+1**“; rechts der Primärknopf. Auf dem Setup-Screen nur der volle Primärknopf „Spiel starten“.

### Toast mit Rückgängig
- Dunkle Kapsel, 14px Radius, 15px Schrift, zentriert 86px über der Unterkante (24px, wenn keine Leiste da ist), rechts „Rückgängig“ in hellem Grün 600. Erscheint mit Opacity und 12px Aufstieg in 0.25s, verschwindet nach 6s. Jede verändernde Aktion (Speichern, Löschen, Revanche, Neues Spiel) meldet sich hier und lässt sich zurücknehmen; es gibt keine Bestätigungsdialoge.

### Bottom Sheet
- Natives `dialog`, unten angedockt, max. 560px breit und 90dvh hoch, 14px obere Rundung, Hintergrund wie die Seite (gruppiert), 36×5px Griff. Fährt in 0.34s mit `cubic-bezier(.32,.72,0,1)` herein, Abdunklung 40% Schwarz blendet in 0.25s ein. Kopf mit Title links und Plain-Button „Fertig“ rechts; Inhalt sind gewöhnliche Gruppen.

### Verlauf
- Eine Gruppe aus aufklappbaren Zeilen (52px): „Runde n“ 600 links, Punkte je Spieler rechts in Sekundärlabel mit Zahl in Label, Chevron dreht sich in 0.2s. Aufgeklappt Detailzeilen „Scope / Meiste Karten / Meiste Denari / Settebello / Primiera“ (Bezeichnung in Sekundärlabel, Wert rechts) und ein roter Zeilen-Button „Runde n löschen“. Leer: zentrierter 15px-Hinweis.

### Abschlussblock
- Gruppe, zentriert, 24/20px Polster: 36px Pokal-Icon in Grün, Headline „Name gewinnt“, Ergebnis „11 : 7 nach 6 Runden“ in Sekundärlabel, darunter zwei Buttons nebeneinander (Primary „Revanche“, Tinted „Neues Spiel“) und ein Link „Letzte Runde zurücknehmen“.

### Bewegung
- Easings: `ease-out` `cubic-bezier(.22,1,.36,1)` für Rückmeldungen, `ease-sheet` `cubic-bezier(.32,.72,0,1)` für das Sheet. Taps auf Zustandsänderungen vibrieren 8ms, wo verfügbar.
- Unter `prefers-reduced-motion: reduce` laufen alle Animationen und Übergänge in 0.01ms, das Hochzählen setzt den Endwert sofort, Scrollen springt statt zu gleiten.

### Sprache
- Deutsch, Anrede in der „ihr“-Form („Tragt …“, „Tippt pro Farbe die höchste Karte.“, „Gebt jedem einen eigenen Namen.“). Italienische Spielbegriffe bleiben italienisch: Scopa/Scope, Denari, Settebello, Primiera, Coppe, Spade, Bastoni, Fante, Cavallo, Re.
- Kurze, sachliche Sätze; Zahlen mit Mittelpunkt verbunden („Runde 3 · bis 11“, „führt · noch 3“), Spielstände mit Doppelpunkt („11 : 7“), Zitate mit deutschen Anführungszeichen („…“).

## Do's and Don'ts

### Do:
- **Do** setze neue Flächen als Gruppe auf den gruppierten Hintergrund: Gruppenfläche, 12px Radius, Zeilen ab 48px mit 16px Einzug und eingerückten 0.5px-Trennlinien.
- **Do** verwende für jede „wer bekommt es“-Frage ein Segmented Control und für Anzahlen einen Stepper mit Count-Wert links daneben.
- **Do** halte Grün für Primäraktion, Auswahl und Führung; Kartenfarben nur im Primiera-Rechner.
- **Do** setze jede wechselnde Zahl in Tabellenziffern.
- **Do** mache jede verändernde Aktion über den Toast mit „Rückgängig“ umkehrbar, statt vorher nachzufragen.
- **Do** definiere neue Farben als Custom Property mit Light- und Dark-Wert.
- **Do** biete für jede Animation den Reduced-Motion-Fall an.

### Don't:
- **Don't** baue Bestätigungsdialoge oder Modal-Popups; Mehrschritt-Inhalte gehören in das Bottom Sheet, Rücknahmen in den Toast.
- **Don't** führe einen zweiten Akzent ein und verwende kein Rosa.
- **Don't** färbe Spieler, Kacheln oder Status in Kartenfarben.
- **Don't** setze Schlagschatten zur Gliederung; Gruppen sind flach, Überlagerungen bekommen Material und Haarlinie.
- **Don't** lade eine Webfont oder eine zweite Schriftfamilie.
- **Don't** lege die Hauptaktion in den Seitenfluss; „Runde speichern“ bleibt in der unteren Leiste.
- **Don't** verändere das App-Icon (cremefarbene Krone auf dunkelgrünem Verlauf).
