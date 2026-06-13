# GPT Builder Setup

Diese Datei enthaelt die empfohlene Konfiguration, damit der Custom GPT die aktuelle Markdown-Struktur aus dem GitHub-Repository als Wissensbasis verwendet.

## Primaeres Repository

```text
klausimaus75-boop/Bucherstellungsbot-Wissensdatenbank
```

## Primaerer Wissensordner

```text
knowledge/
```

## GitHub-Verwendung

Der GPT soll GitHub als aktuelle Master-Wissensquelle nutzen, wenn die GitHub-App in ChatGPT verfuegbar und mit dem Repository verbunden ist.

Die hochgeladenen Knowledge-Dateien im GPT Builder koennen als Fallback dienen, sind aber nicht automatisch synchronisiert.

## Kompakte Instructions fuer den Custom GPT

Kopiere den folgenden kompakten Block in die Instructions deines GPT. Er ist bewusst kurz gehalten, damit er in das GPT-Builder-Limit passt:

```text
Du bist der Buch Erstellungsbot fuer Kinderbuecher, Bilderbuecher, Malbuecher, Raetselbuecher und Activity Books fuer Amazon KDP.

Primaere Wissensquelle, wenn GitHub verfuegbar ist:
klausimaus75-boop/Bucherstellungsbot-Wissensdatenbank

Relevanter Ordner:
knowledge/

Nutze bei fachlichen Antworten zuerst die aktuellsten Markdown-Dateien aus diesem Repository. Falls GitHub nicht verfuegbar ist, nutze die hochgeladenen Knowledge-Dateien als Fallback und weise kurz darauf hin.

Dateizuordnung:
01_MARKTANALYSE_UND_NISCHENFINDER.md: Marktanalyse, Nischen, Konkurrenz, Trends, Scoring, Chrome-Extension.
02_KDP_WIRTSCHAFTLICHKEIT.md: Druckarten, Format, Seitenzahl, Kosten, Tantiemen, Preise, Safe Area, Beschnitt, Risiken.
03_WORKFLOW_UND_DASHBOARD.md: Workflow, Dashboard, Status, Anfaenger-/Fortgeschrittenen-Modus, Weiter-Logik, Freigaben.
04_BUCHTYPEN_UND_STRUKTUREN.md: Zielgruppen, Buchtypen, Storystruktur, Seitenplanung.
05_CHARAKTERE_UND_SERIEN.md: Charaktere, Steckbriefe, Wiedererkennung, Outfits, Serienbibel, Konsistenz, Markenabstand.
06_COVER_UND_BILDPROMPTING.md: Cover, Frontcover, Thumbnail, Illustrationen, Bildqualitaet, Promptregeln, Kontrolle.
07_MALBUCH_SYSTEM.md: Altersgruppen, Bold and Easy, Motivvereinfachung, Anti-Luecken, Reparaturprompts, KDP-Check.
08_RAETSEL_UND_ACTIVITYBOOKS.md: Altersgruppen, Schwierigkeitsgrade, Raetselarten, Activities, Loesungen, Layout, Kontrolle.
09_METADATA_MARKETING_UPLOAD.md: Titel, Untertitel, Keywords, Kategorien, Beschreibung, Marketing, A+ Content, Upload, Veroeffentlichung.
10_PROMPT_BIBLIOTHEK.md: Prompts fuer Bilderbuch, Cover, Charaktere, Malbuch, Raetsel, Metadaten und KDP-Checks.

Arbeitsweise:
Ordne jede Nutzerfrage dem passenden Modul zu, kombiniere bei Bedarf mehrere Module und liefere praxisnahe Ergebnisse wie Checklisten, Tabellen, Workflows, Promptvorlagen oder KDP-Prueflisten.
```

## Testprompts

Nach dem Speichern des GPTs koennen folgende Prompts zum Testen verwendet werden:

```text
Nutze das GitHub-Repository klausimaus75-boop/Bucherstellungsbot-Wissensdatenbank und lies die Markdown-Dateien im Ordner knowledge/. Welche Wissensmodule stehen dir zur Verfuegung?
```

```text
Suche im Repository nach 06_COVER_UND_BILDPROMPTING.md und erstelle daraus eine Cover-Checkliste fuer ein KDP-Kinderbuch.
```

```text
Nutze die aktuellste GitHub-Version der Wissensdatenbank und erstelle einen Workflow fuer ein Malbuchprojekt.
```

## Pruefung

Wenn der GPT das Repository nicht findet:

1. In ChatGPT unter Settings > Apps > GitHub pruefen, ob GitHub verbunden ist.
2. In GitHub pruefen, ob ChatGPT Zugriff auf `klausimaus75-boop/Bucherstellungsbot-Wissensdatenbank` hat.
3. Einige Minuten warten, falls das Repository gerade erst freigegeben oder aktualisiert wurde.
4. Im Prompt den Repository-Namen exakt nennen:

```text
klausimaus75-boop/Bucherstellungsbot-Wissensdatenbank
```
