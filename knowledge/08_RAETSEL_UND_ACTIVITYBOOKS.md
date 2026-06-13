# 08_RAETSEL_UND_ACTIVITYBOOKS.md

# Zweck dieser Datei

Diese Datei definiert alle Regeln für:

- Rätselbücher
- Activity Books
- Lernspiele
- Quizbücher
- Suchbücher
- Escape-Rätsel
- Mitmachbücher

Diese Datei hat Vorrang, sobald Aufgaben, Rätsel oder Mitmachseiten erstellt werden.

---

# GRUNDREGEL

Der GPT erstellt niemals zufällige Rätsel.

Jede Aufgabe benötigt:

- Zielgruppe
- Altersgruppe
- Schwierigkeitsgrad
- klare Aufgabenstellung
- eindeutige Lösung
- ausreichenden Platz
- passende Gestaltung
- Lösungsseite

---

# PRODUKTIONSWORKFLOW

Der GPT arbeitet immer in dieser Reihenfolge:

```text
1. Altersgruppe bestimmen
2. Schwierigkeitsgrad bestimmen
3. Thema bestimmen
4. Rätselart bestimmen
5. Seitenstruktur planen
6. Aufgabe erstellen
7. Lösung erstellen
8. Qualitätsprüfung durchführen
```

---

# ALTERSGRUPPEN

# 3 BIS 5 JAHRE

## Entwicklungsstand

- Vorschule
- erste Konzentrationsübungen
- wenig Lesefähigkeit

---

## Geeignet

- Suchbilder
- Schattenrätsel
- einfache Labyrinthe
- Punkt-zu-Punkt
- Zuordnungsaufgaben

---

## Nicht geeignet

- Kreuzworträtsel
- Escape-Rätsel
- Logikrätsel

---

# 6 BIS 8 JAHRE

## Entwicklungsstand

- Erstlesealter
- einfache Logik möglich

---

## Geeignet

- Wortsuche
- Fehlersuche
- einfache Codes
- Quizfragen
- Bilderrätsel

---

# 9 BIS 12 JAHRE

## Entwicklungsstand

- längere Konzentration
- mehrere Denkschritte möglich

---

## Geeignet

- Logikrätsel
- Escape-Rätsel
- Kreuzworträtsel
- Geheimcodes
- Kombinationsaufgaben

---

# SCHWIERIGKEITSGRADE

# LEICHT

Geeignet für:

- Einsteiger
- jüngere Kinder

---

Regeln:

- sofort verständlich
- wenige Elemente
- schnelle Erfolgserlebnisse

---

# MITTEL

Geeignet für:

- durchschnittliche Zielgruppe

---

Regeln:

- mehrere Schritte möglich
- etwas Nachdenken erforderlich

---

# SCHWER

Geeignet für:

- erfahrene Kinder
- ältere Zielgruppen

---

Regeln:

- mehrere Lösungswege prüfen
- höhere Konzentration erforderlich

---

# SCHWIERIGKEITS-CHECK

Vor jeder Aufgabe prüfen:

```text
Ist die Schwierigkeit passend
zur gewählten Altersgruppe?
```

---

# RÄTSELARTEN

# SUCHBILD

## Ziel

Objekte finden.

---

## Regeln

- Suchobjekte klar erkennbar
- nicht zu klein
- nicht zu viele Objekte

---

# FEHLERSUCHE

## Ziel

Unterschiede erkennen.

---

## Regeln

- Unterschiede fair sichtbar
- nicht mikroskopisch klein

---

# LABYRINTH

## Ziel

Weg finden.

---

## Regeln

- Start klar sichtbar
- Ziel klar sichtbar
- Wege breit genug

---

# SCHATTENRÄTSEL

## Ziel

Objekte zuordnen.

---

## Regeln

- eindeutige Formen
- keine Mehrdeutigkeiten

---

# PUNKT-ZU-PUNKT

## Ziel

Bild verbinden.

---

## Regeln

- altersgerechte Punktanzahl
- Endbild klar erkennbar

---

# WORTSUCHE

## Ziel

Wörter finden.

---

## Regeln

- gut lesbares Raster
- altersgerechte Wörter

---

# KREUZWORTRÄTSEL

## Ziel

Begriffe lösen.

---

## Regeln

- klare Hinweise
- eindeutige Lösungen

---

# QUIZ

## Ziel

Wissen testen.

---

## Regeln

- genau eine richtige Antwort
- keine Fangfragen

---

# LOGIKRÄTSEL

## Ziel

Denken fördern.

---

## Regeln

- nachvollziehbare Lösung
- keine Zufallslösungen

---

# GEHEIMCODE

## Ziel

Information entschlüsseln.

---

## Regeln

- Schlüssel vorhanden
- Lösung überprüfbar

---

# ESCAPE-RÄTSEL

## Ziel

Teil einer Geschichte.

---

## Regeln

- Lösung entsteht logisch
- keine versteckten Informationen
- keine Zufallslösungen

---

# ACTIVITY-BOOK-AUFGABEN

# Verbinden

Kind verbindet passende Elemente.

---

# Ausschneiden

Nur wenn ausdrücklich gewünscht.

---

# Nachzeichnen

Fördert Feinmotorik.

---

# Ausmalen

Kann mit Malbuchseiten kombiniert werden.

---

# Schreiben

Altersgerecht.

---

# ZUORDNEN

Klare Beziehungen.

---

# AUFGABENAUFBAU

Jede Aufgabe erhält:

```text
Aufgabennummer:
Altersgruppe:
Schwierigkeitsgrad:
Thema:
Rätselart:
Aufgabe:
Lösung:
```

---

# LÖSUNGSSEITEN

Pflicht für jedes Rätselbuch.

---

# REGELN

Jede Aufgabe benötigt:

- genau eine Lösung
- korrekte Nummerierung
- vollständige Lösung

---

# LÖSUNGSFORMAT

```text
Aufgabe 1:
Lösung:

Aufgabe 2:
Lösung:
```

---

# LAYOUTREGELN

Jede Seite benötigt:

- Überschrift
- kurze Anleitung
- ausreichend Platz
- klare Struktur

---

# NICHT ERLAUBT

- winzige Schrift
- überladene Seiten
- unklare Aufgaben
- fehlende Lösungen

---

# WEISSRAUMREGEL

Kinder benötigen Platz.

---

Immer ausreichend:

- Randabstände
- Schreibfläche
- Lösungsfläche

---

# QUIZPROMPT

```text
Create a print-ready quiz page for children aged [AGE RANGE] about [TOPIC]. Include a clear heading, one short instruction, [NUMBER] numbered questions, and 3 to 4 answer choices per question. Each question must have exactly one correct answer, no ambiguity, no trick questions, and no misleading options. Use a clean, child-friendly layout with large readable text, enough whitespace, and safe margins. Mark the difficulty as [EASY/MEDIUM/HARD]. Also create the matching answer list.
```

---

# RÄTSELPROMPT

```text
Create a print-ready puzzle book page for children aged [AGE RANGE].

Puzzle type: [PUZZLE TYPE]

Difficulty: [EASY/MEDIUM/HARD]

Theme: [THEME]

The page must include:

- clear title
- short instruction
- child-friendly layout
- enough whitespace
- safe margins
- one verifiable solution

Avoid clutter, tiny details, confusing layouts, decorative overload, and unreadable elements.

Include the answer key.
```

---

# ESCAPE-PROMPT

```text
Create an escape puzzle as part of a continuing children's story for ages [AGE RANGE].

Difficulty: [EASY/MEDIUM/HARD]

The solution must be logically derived from previously provided information.

No random guessing.

No hidden information.

Provide clear page navigation and a verifiable solution.

End with a check: Can a child understand where the solution came from?
```

---

# QUALITÄTSCHECK

Vor Freigabe prüfen:

- Altersgruppe passend?
- Schwierigkeitsgrad passend?
- Aufgabe verständlich?
- Lösung eindeutig?
- Schrift groß genug?
- Platz ausreichend?
- Layout sauber?
- KDP-Safe-Area eingehalten?

---

# FREIGABE-CHECKLISTE

```text
✓ Altersgruppe definiert
✓ Schwierigkeitsgrad definiert
✓ Thema definiert
✓ Rätselart definiert
✓ Aufgabe erstellt
✓ Lösung vorhanden
✓ Layout geprüft
✓ KDP-tauglich
```

---

# ABSCHLUSSREGEL

Eine Rätsel- oder Activity-Seite gilt erst dann als freigegeben, wenn:

- Altersgruppe festgelegt
- Schwierigkeitsgrad festgelegt
- Aufgabe verständlich
- Lösung eindeutig
- Layout geprüft
- Lösungsseite vorhanden

Erst danach darf die Seite in die Buchproduktion übernommen werden.