# 04_BUCHTYPEN_UND_STRUKTUREN.md

# Zweck dieser Datei

Diese Datei definiert:

- Buchtypen
- Zielgruppen
- Storystrukturen
- Seitenplanung
- Textumfang
- Layoutlogik
- Produktionsregeln

Der GPT nutzt diese Datei immer dann, wenn Inhalte geplant oder erstellt werden.

---

# GRUNDREGEL

Bevor Inhalte erstellt werden, müssen feststehen:

```text
Buchtyp
Zielgruppe
Alter
Format
Druckart
```

Der GPT erstellt keine Inhalte ohne diese Informationen.

---

# ZIELGRUPPENLOGIK

## 2 bis 4 Jahre

Merkmale:

- sehr kurze Aufmerksamkeitsspanne
- einfache Sprache
- starke Wiederholungen
- große Illustrationen
- kaum Text

Geeignet:

- Bilderbücher
- erste Mitmachbücher
- einfache Malbücher

Nicht geeignet:

- komplexe Geschichten
- lange Erklärungen
- schwierige Rätsel

---

## 4 bis 6 Jahre

Merkmale:

- erste längere Geschichten möglich
- Humor funktioniert gut
- einfache Aufgaben möglich
- starke visuelle Orientierung

Geeignet:

- Bilderbücher
- Vorlesebücher
- Malbücher
- einfache Activity Books

---

## 6 bis 8 Jahre

Merkmale:

- Erstlesefähigkeit beginnt
- einfache Abenteuer möglich
- erste Kapitel möglich

Geeignet:

- Erstlesebücher
- Vorlesebücher
- Rätselbücher
- Activity Books

---

## 8 bis 10 Jahre

Merkmale:

- längere Aufmerksamkeit
- mehr Handlung möglich
- mehrere Figuren möglich

Geeignet:

- Kinderromane
- Detektivgeschichten
- Abenteuer
- Rätselbücher

---

## 10 bis 12 Jahre

Merkmale:

- komplexere Handlung möglich
- mehrere Konflikte möglich
- stärkere Figurenentwicklung

Geeignet:

- Kinderromane
- Serien
- Escape-Rätsel
- Wissensbücher

---

# BILDERBUCH

## Zielgruppe

3 bis 7 Jahre

---

## Ziel

Vorlesen

Emotion

Nähe

Illustrationen tragen die Geschichte.

---

## Textmenge

Wenig Text.

Die Illustration erzählt mit.

---

## Bilderbuch-Regeln

- jede Seite hat einen Storymoment
- kurze Texte
- starke Bilder
- klare Emotionen
- einfache Handlung

---

## Verboten

- lange Textblöcke
- komplizierte Erklärungen
- viele Figuren gleichzeitig
- mehrere Handlungsstränge

---

# BILDERBUCH-STORYSTRUKTUR

```text
1. Hauptfigur

2. Wunsch

3. Problem

4. Versuch 1

5. Versuch 2

6. Schwieriger Moment

7. Erkenntnis

8. Lösung

9. Warmes Ende
```

---

# BILDERBUCH-SEITENFORMAT

Jede Seite erhält:

```text
Seite:

Storymoment:

Text:

Bildidee:

Textbereich:

Bildprompt:

Check:
```

---

# VORLESEBUCH

## Zielgruppe

4 bis 8 Jahre

---

## Ziel

Gemeinsames Vorlesen

---

## Regeln

- mehr Text als Bilderbuch
- natürliche Sprache
- klare Abschnitte
- ruhiger Lesefluss

---

## Verboten

- verschachtelte Sätze
- komplizierte Zeitsprünge
- zu viele Figuren

---

# VORLESEBUCH-STRUKTUR

```text
Einleitung

Problem

Abenteuer

Lösung

Positives Ende
```

---

# ERSTLESEBUCH

## Zielgruppe

6 bis 9 Jahre

---

## Ziel

Selbstständiges Lesen fördern

---

## Regeln

- kurze Sätze
- einfache Wörter
- große Schrift
- kurze Kapitel

---

## Kapitelanfangsseiten

Richtwert:

```text
100 bis 140 Wörter
```

---

## Folgeseiten

Richtwert:

```text
160 bis 220 Wörter
```

---

## Verboten

- schwierige Fremdwörter
- lange Absätze
- komplizierte Satzkonstruktionen

---

# ERSTLESEBUCH-STRUKTUR

```text
Kapitel 1
Einführung

Kapitel 2
Problem

Kapitel 3
Abenteuer

Kapitel 4
Lösung

Kapitel 5
Abschluss
```

---

# KINDERROMAN

## Zielgruppe

8 bis 12 Jahre

---

## Ziel

Längere Handlung

Figurenentwicklung

Spannung

---

## Regeln

- klarer roter Faden
- nachvollziehbare Entwicklung
- konsistente Figuren
- logische Ortswechsel

---

## Verboten

- Zufallslösungen
- Figurenwechsel ohne Erklärung
- Handlungssprünge

---

# KINDERROMAN-STRUKTUR

```text
Einführung

Auslöser

Abenteuer

Konflikt

Rückschlag

Erkenntnis

Finale

Positives Ende
```

---

# MALBUCH

## Zielgruppe

2 bis 12 Jahre

---

## Ziel

Ausmalen

Entspannung

Kreativität

---

## Regeln

- große Motive
- klare Konturen
- altersgerechter Detailgrad

---

## Priorität

Für Malbücher gilt zusätzlich:

```text
07_MALBUCH_SYSTEM.md
```

hat Vorrang.

---

# RÄTSELBUCH

## Zielgruppe

3 bis 12 Jahre

---

## Ziel

Lernen durch Spielen

---

## Regeln

- jede Aufgabe braucht eine Lösung
- Lösungsseiten sind Pflicht
- genügend Platz für Antworten

---

## Priorität

Für Rätselbücher gilt zusätzlich:

```text
08_RAETSEL_UND_ACTIVITYBOOKS.md
```

hat Vorrang.

---

# ACTIVITY BOOK

## Zielgruppe

3 bis 12 Jahre

---

## Ziel

Mitmachen

Lernen

Entdecken

Kreativität

---

## Regeln

- abwechslungsreiche Aufgaben
- klare Anweisungen
- ausreichend Weißraum
- altersgerechte Schwierigkeit

---

## Verboten

- überladene Seiten
- winzige Schrift
- unklare Aufgaben

---

# STORYPLANUNG

Der GPT plant immer zuerst:

```text
Geschichte
```

und danach:

```text
Seiten
```

Nicht umgekehrt.

---

# STANDARD-STORYMODELL

```text
1. Hauptfigur

2. Wunsch

3. Problem

4. Auslöser

5. Versuch 1

6. Versuch 2

7. Rückschlag

8. Erkenntnis

9. Lösung

10. Positives Ende
```

---

# CHARAKTERE

Vor Produktionsbeginn erhalten Hauptfiguren einen Steckbrief.

Pflichtfelder:

```text
Name:
Alter:
Rolle:
Wunsch:
Problem:
Stärke:
Schwäche:
Wiedererkennungsmerkmal:
Optik:
```

Weitere Details:

```text
05_CHARAKTERE_UND_SERIEN.md
```

---

# SEITENPLANUNG

Vor dem Schreiben erstellt der GPT immer einen Plan.

---

## Bilderbuch

Seitenplan vor Text.

---

## Erstlesebuch

Kapitelplan vor Text.

---

## Kinderroman

Kapitelübersicht vor Text.

---

## Rätselbuch

Aufgabenübersicht vor Gestaltung.

---

# LOGIKPRÜFUNG

Vor jeder neuen Seite prüfen:

- Handlung logisch?
- Figuren konsistent?
- Namen korrekt?
- Orte korrekt?
- Emotionen passend?
- Zielgruppe passend?

---

# SPRACHREGELN

Kinderbuchsprache soll sein:

- warm
- klar
- modern
- verständlich
- altersgerecht

---

# VERMEIDEN

- KI-Floskeln
- unnötige Wiederholungen
- moralische Predigten
- überlange Sätze
- unverständliche Begriffe

---

# ABSCHLUSSREGEL

Der GPT erstellt Inhalte erst dann, wenn:

- Zielgruppe definiert ist
- Buchtyp feststeht
- Struktur geplant wurde

Er plant immer zuerst die Struktur und danach die eigentlichen Inhalte.