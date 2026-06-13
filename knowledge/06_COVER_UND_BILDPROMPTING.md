# 06_COVER_UND_BILDPROMPTING.md

# Zweck dieser Datei

Diese Datei definiert alle Regeln für:

- Frontcover
- Rückcover
- Coverkonzepte
- Bilderbuchillustrationen
- Innenbuchillustrationen
- Bildprompts
- Illustrationsqualität
- Thumbnail-Wirkung
- Amazon-KDP-Coverlogik

Diese Datei hat Vorrang bei:

- Coverentwicklung
- Coverbewertung
- Bilderbuchillustrationen
- Innenbuchproduktion
- Illustrationsprompts

---

# DESIGNPHILOSOPHIE

Ein gutes Cover verkauft nicht durch Dekoration.

Ein gutes Cover verkauft durch:

- Klarheit
- Lesbarkeit
- Fokus
- Emotion
- Wiedererkennung

---

# LEITSATZ

```text
Weniger Dekoration.
Mehr Wirkung.
Mehr Lesbarkeit.
```

---

# DESIGNZIELE

Jedes Cover soll:

- professionell wirken
- modern wirken
- original wirken
- klar lesbar sein
- als Thumbnail funktionieren
- zur Zielgruppe passen

---

# VERMEIDEN

Standardmäßig vermeiden:

- Vintagefilter
- Gelbstich
- Sepia
- Retrooptik
- Filmkorn
- Bildrauschen
- übertriebene Glow-Effekte
- übertriebene Glitzereffekte
- chaotische Hintergründe
- Clipart-Look
- KI-Massenware
- überladene Cover

---

# COVER-PLANUNG

Vor jeder Coverentwicklung bestimmt der GPT:

```text
Buchtyp:
Zielgruppe:
Alter:
Hauptversprechen:
Titel:
Untertitel:
USP:
Hauptmotiv:
Farbwelt:
```

---

# COVER-WORKFLOW

Der GPT arbeitet in dieser Reihenfolge:

```text
1. Buchtyp bestimmen
2. Zielgruppe bestimmen
3. Hauptversprechen bestimmen
4. Hauptmotiv bestimmen
5. Farbwelt bestimmen
6. Titelhierarchie planen
7. Frontcover planen
8. Frontcover freigeben
9. Rückcover planen
10. Gesamtcover erstellen
```

---

# WICHTIGE COVERREGEL

Zuerst immer:

```text
Frontcover
```

Nicht zuerst:

```text
Rückcover
Buchrücken
Komplettcover
Mockup
```

---

# FRONTCOVER-REGEL

Der GPT entwickelt zuerst ein flaches Frontcover.

---

# NICHT ALS COVERBEWERTUNG VERWENDEN

Keine Bewertung anhand von:

- 3D-Mockups
- Perspektivansichten
- aufgestellten Büchern
- Marketingbildern

---

# THUMBNAIL-TEST

Vor jeder Freigabe prüfen:

```text
Ist der Titel lesbar?

Ist die Zielgruppe erkennbar?

Ist das Hauptmotiv sichtbar?

Ist das Genre erkennbar?

Wirkt das Cover professionell?
```

---

# TITELHIERARCHIE

## Reihenname

- klein
- unterstützend
- Wiedererkennung

---

## Haupttitel

- größte Schrift
- höchste Aufmerksamkeit
- sofort lesbar

---

## Untertitel

- Nutzen erklären
- Thema erklären
- kleiner als Haupttitel

---

## Autorname

- sichtbar
- aber nicht dominierend

---

# COVER NACH BUCHTYP

## BILDERBUCH

Verkauft:

- Emotion
- Figur
- Stimmung

Pflicht:

- starke Hauptfigur
- warme Farben
- klare Szene

---

## ERSTLESEBUCH

Verkauft:

- Abenteuer
- Humor
- Lesefreude

Pflicht:

- sehr lesbarer Titel
- klare Figur
- klare Handlungsidee

---

## MALBUCH

Verkauft:

- Motivwelt
- Ausmalstil
- Spaßfaktor

Pflicht:

- Motiv sofort sichtbar
- Bold-and-Easy-Stil erkennbar

---

## RÄTSELBUCH

Verkauft:

- Neugier
- Erfolgserlebnis
- Entdecken

Pflicht:

- klares Symbol
- wenig Überladung

---

## SACHBUCH

Verkauft:

- Vertrauen
- Struktur
- Wissen

Pflicht:

- saubere Typografie
- klare Ordnung

---

# FARBWELT

Die Farbwelt muss:

- zur Zielgruppe passen
- konsistent sein
- den Fokus unterstützen

Vermeiden:

- zu viele Farben
- Neonchaos
- unruhige Farbmischungen

---

# INNENBUCH-PRODUKTION

Diese Regeln gelten für:

- Bilderbücher
- Vorlesebücher
- Erstlesebücher
- Kinderromane mit Illustrationen

---

# GRUNDREGEL

Innenbuchseiten werden immer einzeln produziert.

Jede Seite ist eine eigenständige Produktionsaufgabe.

Der GPT erstellt niemals das komplette Innenbuch in einem Schritt.

---

# PRODUKTIONSREIHENFOLGE

Für jede neue Seite:

```text
1. Storymoment bestimmen

2. Seitenziel bestimmen

3. Text festlegen

4. Bildidee festlegen

5. Textbereich festlegen

6. Bildprompt erstellen

7. Qualitätscheck durchführen
```

---

# PFLICHTAUSGABE PRO SEITE

Der GPT verwendet:

```text
Seite:

Storymoment:

Text:

Bildidee:

Textbereich:

Bildprompt:

[Codebox]

Qualitätscheck:
```

---

# QUALITÄTSCHECK

Mindestens prüfen:

```text
- Textbereich vorhanden

- Safe Area vorhanden

- Hauptfigur sichtbar

- Fokus klar

- Zielgruppe passend

- Stil konsistent
```

---

# BILDPROMPT-REGEL

Für jede neue Buchseite wird genau ein eigener Bildprompt erstellt.

Jeder Bildprompt wird separat in einer eigenen Codebox ausgegeben.

---

# NICHT ERLAUBT

Mehrere Seiten in einem einzigen Prompt.

Beispiel:

```text
Seite 1
Seite 2
Seite 3
```

in einem gemeinsamen Prompt.

---

# ERLAUBT

Seite 1

```text
Prompt Seite 1
```

Seite 2

```text
Prompt Seite 2
```

Seite 3

```text
Prompt Seite 3
```

---

# DOPPELSEITEN

Wenn eine Doppelseite geplant wird:

Die Doppelseite gilt als eine Illustration.

Es wird ein gemeinsamer Prompt erstellt.

---

# SEITENKONSISTENZ

Vor jeder neuen Seite prüfen:

```text
Figur identisch?

Kleidung identisch?

Farben identisch?

Accessoires identisch?

Illustrationsstil identisch?

Zielgruppe identisch?
```

---

# BILDERBUCH-ILLUSTRATIONEN

## Grundregel

Illustrationen werden als vollständige Buchseiten geplant.

---

# JEDE SEITE BRAUCHT

- Storymoment
- Hauptfokus
- Textbereich
- sichere Ränder

---

# TEXTBEREICH

Textbereiche werden integriert.

Geeignete Bereiche:

- Himmel
- Wand
- Wiese
- Schnee
- Wasser
- freie helle Fläche

---

# VERBOTEN

- weiße Textboxen
- harte Rahmen
- Figuren hinter Text
- Muster hinter Text
- dunkle Flächen hinter Text

---

# KOMPOSITION

Der Blick des Lesers soll geführt werden.

---

# REGELN

- klarer Fokus
- keine Überladung
- ruhiger Hintergrund
- genügend Weißraum

---

# BILDQUALITÄT

Jede Illustration soll:

- professionell wirken
- druckfähig wirken
- modern wirken

---

# VERMEIDEN

- unscharfe Gesichter
- matschige Details
- deformierte Hände
- chaotische Hintergründe
- KI-Artefakte

---

# BILDPROMPT-REGELN

Immer:

- Englisch
- eine Szene
- ein Bild
- ein Prompt
- eine Seite

---

# AUSGABEFORM

```text
Prompt:

[Codebox]
```

---

# STANDARDPROMPT BILDERBUCH

```text
A modern, high-quality children's book illustration for [AGE RANGE], showing [SCENE]. The composition is designed as a full book page with a calm integrated light text area in [TEXT AREA POSITION]. Main character: [CHARACTER]. Mood: [MOOD]. Style: polished contemporary children's book illustration, clear shapes, warm but clean colors, professional publishing quality, strong focal point, generous safe margins, no hard text box, no border, no vintage filter, no yellow tint, no grain, no blurry details, no overdecorated background, no text in the image.
```

---

# STANDARDPROMPT COVER

```text
Create a flat front cover design for a [BOOK TYPE] for [AGE RANGE]. Theme: [THEME]. Main visual: [MAIN VISUAL]. Mood: [MOOD]. The cover should look modern, professional, high-quality, marketable, and original, with a strong focal point, clear title hierarchy, generous safe margins, excellent Amazon thumbnail readability, and a clean contemporary color palette. Include planned space for title, subtitle, author name, and optional USP badge inside the safe area. No 3D mockup, no book fold, no perspective, no border, no vintage filter, no yellow tint, no grain, no blurry details, no glitter overload, no chaotic background, no copied brand style, no text errors.
```

---

# UNIVERSALER QUALITÄTSBLOCK

Kann an Prompts angehängt werden:

```text
modern professional children's book quality, clear focal point, clean composition, generous safe margins, polished illustration, no vintage filter, no yellow tint, no grain, no blur, no muddy details, no excessive glow, no glitter overload, no chaotic background, no copied brand style, no text, no watermark
```

---

# COVER-FREIGABECHECK

Vor Freigabe prüfen:

- Buchtyp erkennbar?
- Zielgruppe erkennbar?
- Titel lesbar?
- Hauptmotiv stark?
- USP sinnvoll?
- Thumbnail stark?
- nicht überladen?
- keine Markenähnlichkeit?
- Safe Area berücksichtigt?

---

# MARKEN- UND RECHTESCHUTZ

Nicht imitieren:

- Disney
- Pixar
- Pokémon
- Marvel
- Bluey
- Paw Patrol
- Harry Potter

---

# ORIGINALITÄTSREGEL

Wenn Ähnlichkeiten auftreten:

```text
Das wirkt zu nah an bekanntem Material.

Ich entwickle eine eigenständige Alternative mit anderer Figur, anderer Farbwelt und anderer visueller Identität.
```

---

# FREIGABE INNENBUCHSEITE

Eine Innenbuchseite gilt erst als freigegeben wenn:

```text
✓ Storymoment klar

✓ Text freigegeben

✓ Textbereich geplant

✓ Bildprompt erstellt

✓ Qualitätscheck bestanden
```

---

# ABSCHLUSSREGEL

Ein Cover gilt erst dann als freigegeben, wenn:

- Thumbnail-Test bestanden
- Zielgruppe erkennbar
- Titel lesbar
- Hauptmotiv klar
- keine Markenähnlichkeit
- Frontcover freigegeben

Erst danach darf Rückcover oder Gesamtcover geplant werden.