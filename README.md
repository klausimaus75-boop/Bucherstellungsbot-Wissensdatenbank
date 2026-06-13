# Buch Erstellungsbot

## Projektbeschreibung

Dieses Repository ist die zentrale Wissensdatenbank fuer einen Custom GPT zur professionellen Erstellung von Kinderbuechern, Bilderbuechern, Malbuechern, Raetselbuechern und Activity Books fuer Amazon KDP.

Der Buch Erstellungsbot soll Autorinnen, Autoren und Publisher dabei unterstuetzen, Buchideen strukturiert zu entwickeln, Marktchancen einzuschaetzen, Inhalte zu planen, Bild- und Coverprompts zu formulieren und den Upload bei Amazon KDP vorzubereiten.

## Zielsetzung

- Aufbau einer wartbaren Wissensbasis fuer einen Custom GPT
- Standardisierung von Workflows fuer verschiedene Buchtypen
- Vorbereitung auf spaetere Marktanalyse- und Chrome-Extension-Anbindungen
- Sammlung wiederverwendbarer Promptmuster
- Dokumentation von KDP-relevanten Regeln, Pruefungen und Prozessen

## Wissensarchitektur

Die Wissensbasis ist modular aufgebaut. Jede Datei im Ordner `knowledge/` behandelt einen klar abgegrenzten Themenbereich und kann unabhaengig erweitert werden.

```text
Buch-Erstellungsbot/
├── README.md
├── knowledge/
│   ├── 01_MARKTANALYSE_UND_NISCHENFINDER.md
│   ├── 02_KDP_WIRTSCHAFTLICHKEIT.md
│   ├── 03_WORKFLOW_UND_DASHBOARD.md
│   ├── 04_BUCHTYPEN_UND_STRUKTUREN.md
│   ├── 05_CHARAKTERE_UND_SERIEN.md
│   ├── 06_COVER_UND_BILDPROMPTING.md
│   ├── 07_MALBUCH_SYSTEM.md
│   ├── 08_RAETSEL_UND_ACTIVITYBOOKS.md
│   ├── 09_METADATA_MARKETING_UPLOAD.md
│   └── 10_PROMPT_BIBLIOTHEK.md
├── extensions/
└── assets/
```

## Workflowuebersicht

Der spaetere Custom GPT soll Nutzer schrittweise durch folgende Phasen fuehren:

1. Markt- und Nischenanalyse
2. Buchtyp- und Zielgruppenentscheidung
3. Wirtschaftlichkeitspruefung fuer Amazon KDP
4. Strukturplanung und Seitenaufbau
5. Charakter-, Serien- und Stilentwicklung
6. Cover-, Bild- und Promptplanung
7. Qualitaetskontrolle fuer Inhalt, Layout und Upload
8. Metadaten, Marketing und Veroeffentlichung

## Dateibeschreibungen

| Datei | Zweck |
| --- | --- |
| `01_MARKTANALYSE_UND_NISCHENFINDER.md` | Markt-, Trend-, Konkurrenz- und Nischenbewertung |
| `02_KDP_WIRTSCHAFTLICHKEIT.md` | KDP-Formate, Druckkosten, Tantiemen und Preisstrategie |
| `03_WORKFLOW_UND_DASHBOARD.md` | Projektsteuerung, Modi, Statuslogik und Freigabeprozesse |
| `04_BUCHTYPEN_UND_STRUKTUREN.md` | Buchtypen, Zielgruppen, Storystrukturen und Seitenplanung |
| `05_CHARAKTERE_UND_SERIEN.md` | Charakterentwicklung, Wiedererkennung und Serienbibel |
| `06_COVER_UND_BILDPROMPTING.md` | Coverplanung, Illustration, Promptregeln und Bildkontrolle |
| `07_MALBUCH_SYSTEM.md` | Malbuchlogik, Motivvereinfachung und KDP-Pruefung |
| `08_RAETSEL_UND_ACTIVITYBOOKS.md` | Raetselarten, Activity-Aufgaben, Loesungen und Layoutregeln |
| `09_METADATA_MARKETING_UPLOAD.md` | Titel, Keywords, Kategorien, Beschreibung, Marketing und Upload |
| `10_PROMPT_BIBLIOTHEK.md` | Wiederverwendbare Prompts fuer alle Arbeitsbereiche |

## Zusaetzliche Ordner

### `extensions/`

Dieser Ordner ist fuer spaetere Dokumentationen zu Chrome-Extensions, externen Datenschnittstellen und Marktanalyse-Integrationen vorgesehen.

### `assets/`

Dieser Ordner ist fuer Referenzbilder, Stilboards, Coverbeispiele und Charakterboards vorgesehen.

## Spaetere Erweiterungen

- Chrome-Extension-Dokumentation fuer Marktanalyse
- Schnittstellenbeschreibungen fuer BSR-, Keyword- und Trenddaten
- Beispielprojekte fuer verschiedene Buchtypen
- Checklisten fuer KDP-Upload und Qualitaetspruefung
- Erweiterte Promptbibliothek mit getesteten Promptmustern
- Serienbibel-Vorlagen fuer wiederkehrende Charaktere
- Dashboard-Logik fuer Projektstatus und Freigabeprozesse

